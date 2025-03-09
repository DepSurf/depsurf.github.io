# Function: <code>clk_prepare_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584145367,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:467",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584586956,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:467",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584654005,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:467",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585273698,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:467",
      "file": "drivers/usb/phy/phy-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585292868,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:467",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585387055,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:467",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585415423,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:467",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584482351,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:483",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584935265,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:483",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585001473,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:483",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585678921,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:483",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585783375,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:483",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585811407,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:483",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
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
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584664478,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:507",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585118652,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:507",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585132375,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:507",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585184929,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:507",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585860620,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:507",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585972111,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:507",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586000079,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:507",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
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
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584746592,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584752573,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585199440,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585213877,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585267113,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585946974,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586055873,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586083505,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586345104,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk"
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
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585162128,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585169849,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585627600,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585642021,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585695209,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586390094,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586500289,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586527985,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586809568,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:639",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk"
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
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585394630,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:701",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585405835,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:701",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585872083,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:701",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585887174,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:701",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585941626,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:701",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586650444,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:701",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764749,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:701",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586791949,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:701",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587077755,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:701",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584484521,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:822",
      "file": "drivers/pci/controller/dwc/pci-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518022,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:822",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585529035,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:822",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586007955,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:822",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586022869,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:822",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586077802,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:822",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586802268,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:822",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586922301,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:822",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586949085,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:822",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587238027,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:822",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584682309,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:900",
      "file": "drivers/pci/controller/dwc/pci-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585738987,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:900",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585746913,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:900",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586251981,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:900",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586265093,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:900",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586312999,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:900",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587060428,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:900",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587181916,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:900",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587209486,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:900",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587505036,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:900",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585881227,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585889153,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586400189,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586413317,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461175,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587260796,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587382140,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587409742,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587708172,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586615979,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:906",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586626561,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:906",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587175792,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:906",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587187349,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:906",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587238656,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:906",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588114828,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:906",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588241372,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:906",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588269550,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:906",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588577932,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:906",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585403818,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:924",
      "file": "drivers/gpio/gpio-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-xilinx.c:xgpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586726093,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:924",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586736097,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:924",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587259296,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:924",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587267861,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:924",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587308112,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:924",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588157185,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:924",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588277132,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:924",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304670,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:924",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601996,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:924",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586223682,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586609601,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586619713,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587024735,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587147744,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587156197,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587194314,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588038993,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588160220,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588187918,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588486108,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586729970,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587152868,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587162033,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587591487,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587723598,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587756239,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588659889,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588663015,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588798744,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588827980,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589154540,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588002821,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588458354,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588472853,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588929457,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589067821,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589101222,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590076769,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590080179,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590221837,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590252493,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590606940,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:946",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int clk_prepare_enable(struct clk * clk)
```

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589278071,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/clk/clk-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589373759,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589893894,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589907166,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590442949,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590597821,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590637062,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591684817,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591688547,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591840013,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591872685,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592267100,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589277152,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int clk_prepare_enable(struct clk * clk)
```

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589574663,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/clk/clk-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589672383,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590203093,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590762629,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590977892,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592107955,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592111851,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592262941,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592296093,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592692412,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589573744,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int clk_prepare_enable(struct clk * clk)
```

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589884103,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/clk/clk-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589983087,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590544279,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591104869,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591321860,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592848387,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592852283,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593004029,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593037405,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593438060,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:1068",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589883184,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int clk_prepare_enable(struct clk * clk)
```

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496437572,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/irqchip/irq-imx-irqsteer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496469260,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/bus/imx-weim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/imx-weim.c:weim_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496469480,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/bus/qcom-ebi2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496488680,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/phy/phy-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-xgene.c:xgene_phy_hw_init",
        "drivers/phy/phy-xgene.c:xgene_phy_hw_init",
        "drivers/phy/phy-xgene.c:xgene_phy_hw_init",
        "drivers/phy/phy-xgene.c:xgene_phy_hw_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496586584,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496670784,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pinctrl/sunxi/pinctrl-sunxi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496766332,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/gpio/gpio-davinci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496768908,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496776292,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/gpio/gpio-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496784132,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/gpio/gpio-mxc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497099912,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pci-ftpci100.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497110088,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pcie-rcar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497139268,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pcie-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497146916,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pcie-mediatek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497175672,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pci-imx6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497189096,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pcie-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497191720,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pcie-armada8k.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497192596,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pcie-kirin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497195968,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pcie-histb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497209484,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pci-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497370064,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/video/fbdev/simplefb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497730392,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_get_enable_pclk",
        "drivers/amba/bus.c:amba_get_enable_pclk",
        "drivers/amba/bus.c:amba_pm_runtime_resume",
        "drivers/amba/bus.c:amba_pm_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497813080,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/bcm/clk-bcm2835.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497831592,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/imx/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk.c:imx_register_uart_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497909548,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/mediatek/clk-mt7622.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497911488,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/mediatek/clk-mt8173.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical"
      ]
    },
    {
      "addr": 18446603336497936024,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/renesas/rcar-usb2-clock-sel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511167920,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/rockchip/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk.c:rockchip_clk_protect_critical"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497949400,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/rockchip/clk-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511180664,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/sunxi/clk-simple-gates.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497968952,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/sunxi/clk-sun9i-mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497969908,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/sunxi/clk-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert",
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert",
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert",
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497995232,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/sunxi-ng/ccu-sun8i-de2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498053136,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_xor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498057180,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/dma/mv_xor_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511188976,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/dma/mxs-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511190176,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498078532,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/bcm/bcm2835-power.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498119052,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/imx/gpcv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498123084,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/mediatek/mtk-scpsys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498126772,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/amlogic/meson-gx-pwrc-vpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498615152,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/8250/8250_dw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498620852,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498623980,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_of.c:of_serial_resume",
        "drivers/tty/serial/8250/8250_of.c:of_serial_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498628552,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498648496,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498651468,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_freeze",
        "drivers/tty/serial/imx.c:imx_uart_freeze",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498668876,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/meson_uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498675992,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498682940,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498695272,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/mvebu-uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498916508,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/iommu/qcom_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499247188,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499276756,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499329180,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499822764,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/ata/ahci_imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx_sata_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499842280,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/ata/libahci_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libahci_platform.c:ahci_platform_enable_clks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499956972,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/net/phy/mdio-mux-bcm-iproc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_resume",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_resume",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500011192,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500353212,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/phy/phy-mxs-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500371804,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500505804,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ehci-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511250056,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/rtc/rtc-mv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-mv.c:mv_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500826324,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/rtc/rtc-rtd119x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500827052,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/rtc/rtc-sun6i.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500830752,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/rtc/rtc-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-xgene.c:xgene_rtc_resume",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_resume",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_probe",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500873724,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500890932,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/i2c/busses/i2c-sprd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_runtime_resume",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_runtime_resume",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501041788,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/watchdog/rtd119x_wdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501453396,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_runtime_resume",
        "drivers/mmc/host/mmci.c:mmci_runtime_resume",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/mmci.c:mmci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501490676,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/firmware/qcom_scm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511290788,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/timer-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-of.c:timer_of_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501585152,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/timer-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe"
      ]
    },
    {
      "addr": 18446603336501670976,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mailbox/rockchip-mailbox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501740084,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/memory/mtk-smi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/mtk-smi.c:mtk_smi_common_resume",
        "drivers/memory/mtk-smi.c:mtk_smi_common_resume",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_resume",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497911488,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336501585152,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int clk_prepare_enable(struct clk * clk)
```

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243269780,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "arch/arm/kernel/smp_twd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp_twd.c:twd_local_timer_of_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3243299828,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "arch/arm/mach-mvebu/mvebu-soc-id.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224574604,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "arch/arm/mach-mvebu/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/platsmp.c:armada_xp_sync_secondary_clk",
        "arch/arm/mach-mvebu/platsmp.c:armada_xp_sync_secondary_clk"
      ],
      "caller_func": [
        "arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus"
      ]
    },
    {
      "addr": 3243305860,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "arch/arm/mach-imx/pm-imx5.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224580540,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "arch/arm/mach-imx/mmdc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3224593820,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "arch/arm/mach-omap2/display.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/display.c:omap_dss_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3229758544,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/irqchip/irq-imx-irqsteer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229763860,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/bus/imx-weim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/imx-weim.c:weim_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229771080,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/bus/qcom-ebi2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229793864,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/phy/marvell/phy-mvebu-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 3229797108,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/phy/samsung/phy-exynos5250-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229866800,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pinctrl/pinctrl-rzn1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229901672,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229924460,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pinctrl/mvebu/pinctrl-dove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230042380,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230049400,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/gpio/gpio-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230057468,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/gpio/gpio-mxc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230087300,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/gpio/gpio-vf610.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-vf610.c:vf610_gpio_probe",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_probe",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_probe",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230302360,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pci-ftpci100.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230309384,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pci-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230321164,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pci-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3230331036,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pcie-rcar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230338648,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pci-v3-semi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230350580,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pcie-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3230359812,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pcie-mediatek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port"
      ],
      "caller_func": []
    },
    {
      "addr": 3230382588,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pci-imx6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3230391248,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pcie-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0"
      ],
      "caller_func": []
    },
    {
      "addr": 3230392660,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pcie-armada8k.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230395216,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pcie-histb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230396984,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pcie-uniphier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230546540,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/video/fbdev/simplefb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230553748,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_get_enable_pclk",
        "drivers/amba/bus.c:amba_get_enable_pclk",
        "drivers/amba/bus.c:amba_pm_runtime_resume",
        "drivers/amba/bus.c:amba_pm_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3230636140,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/imx/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk.c:imx_register_uart_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3230655532,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/imx/clk-imx5.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx50_clocks_init"
      ]
    },
    {
      "addr": 3230656128,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/imx/clk-imx6q.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init"
      ]
    },
    {
      "addr": 3230656364,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/imx/clk-imx6sl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init"
      ]
    },
    {
      "addr": 3230656424,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/imx/clk-imx6sx.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init",
        "drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init"
      ]
    },
    {
      "addr": 3230656484,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/imx/clk-imx6ul.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init",
        "drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init"
      ]
    },
    {
      "addr": 3243752360,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/imx/clk-vf610.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230665728,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/mediatek/clk-mt7622.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230668032,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/mediatek/clk-mt7629.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230669300,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/mediatek/clk-mt8135.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/mediatek/clk-mt8135.c:mtk_infrasys_init",
        "drivers/clk/mediatek/clk-mt8135.c:mtk_topckgen_init"
      ]
    },
    {
      "addr": 3230669360,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/mediatek/clk-mt8173.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical",
        "drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical"
      ]
    },
    {
      "addr": 3230682204,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/renesas/rcar-usb2-clock-sel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3243782156,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/rockchip/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk.c:rockchip_clk_protect_critical"
      ],
      "caller_func": []
    },
    {
      "addr": 3230696040,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/rockchip/clk-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk"
      ],
      "caller_func": []
    },
    {
      "addr": 3243792964,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/samsung/clk-exynos5420.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/samsung/clk-exynos5420.c:exynos5x_clk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243794752,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/tegra/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk.c:tegra_init_from_table"
      ],
      "caller_func": []
    },
    {
      "addr": 3230739840,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/tegra/clk-emc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-emc.c:emc_set_timing"
      ],
      "caller_func": []
    },
    {
      "addr": 3230752020,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/ti/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/ti/clk.c:omap2_clk_enable_init_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3243824772,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/ti/clk-814x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/ti/clk-814x.c:dm814x_adpll_enable_init_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3230770636,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/ti/clk-3xxx.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5",
        "drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5"
      ]
    },
    {
      "addr": 3243826724,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clk/ti/clk-7xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230817928,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_xor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3243829776,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/dma/mxs-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 3243830852,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230833472,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/dma/tegra20-apb-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3230876280,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/imx/gpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/imx/gpc.c:imx6_pm_domain_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 3230879220,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/imx/gpcv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req"
      ],
      "caller_func": []
    },
    {
      "addr": 3230882292,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/mediatek/mtk-scpsys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 3230887108,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/amlogic/meson-gx-pwrc-vpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230901508,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/tegra/fuse/fuse-tegra30.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3230902428,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/tegra/fuse/fuse-tegra20.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3230904300,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/soc/tegra/pmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/pmc.c:tegra_powergate_enable_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3231012068,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/regulator/fixed.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/fixed.c:reg_clock_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3231243704,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3231246648,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_of.c:of_serial_resume",
        "drivers/tty/serial/8250/8250_of.c:of_serial_resume",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3231254748,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231267060,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231278100,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_freeze",
        "drivers/tty/serial/imx.c:imx_uart_freeze",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3231289792,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/meson_uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231293056,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231299152,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 3231325840,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/mvebu-uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231489528,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/iommu/exynos-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3231499676,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/iommu/qcom_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3231752356,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231786880,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/t7l66xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_resume",
        "drivers/mfd/t7l66xb.c:t7l66xb_resume",
        "drivers/mfd/t7l66xb.c:t7l66xb_mmc_enable",
        "drivers/mfd/t7l66xb.c:t7l66xb_mmc_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3231788624,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/tc6387xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc6387xb.c:tc6387xb_mmc_enable",
        "drivers/mfd/tc6387xb.c:tc6387xb_mmc_enable",
        "drivers/mfd/tc6387xb.c:tc6387xb_resume",
        "drivers/mfd/tc6387xb.c:tc6387xb_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3231792464,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/tc6393xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231800084,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3231879180,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3231930004,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/omap-usb-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3232266896,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/ata/libahci_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libahci_platform.c:ahci_platform_enable_clks"
      ],
      "caller_func": []
    },
    {
      "addr": 3232279200,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/ata/ahci_imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3232535836,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232808164,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/phy/phy-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/usb/phy/phy-generic.c:nop_set_suspend",
        "drivers/usb/phy/phy-generic.c:nop_set_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232811160,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/phy/phy-mxs-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3232828776,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3232956432,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ehci-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232958596,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ehci-exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_resume",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_resume",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_probe",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232991452,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ohci-exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_resume",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_resume",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_probe",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232999956,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3243902156,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/rtc/rtc-mv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-mv.c:mv_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233335144,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/rtc/rtc-omap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-omap.c:omap_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233345084,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/rtc/rtc-s3c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233382776,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233397636,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/i2c/busses/i2c-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233408036,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/i2c/busses/i2c-s3c2410.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233540236,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/thermal/samsung/exynos_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233811744,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/cpufreq/tegra20-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_cpu_init",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_cpu_init",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_target_intermediate",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_target_intermediate"
      ],
      "caller_func": []
    },
    {
      "addr": 3233812248,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/cpufreq/tegra124-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233939536,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_runtime_resume",
        "drivers/mmc/host/mmci.c:mmci_runtime_resume",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/mmci.c:mmci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233989176,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mmc/host/omap_hsmmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios"
      ],
      "caller_func": []
    },
    {
      "addr": 3233992872,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mmc/host/sdhci-pltfm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3234001324,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mmc/host/sdhci-esdhc-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234028696,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/firmware/qcom_scm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243942764,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/timer-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-of.c:timer_of_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243944028,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/renesas-ostm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/renesas-ostm.c:ostm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3234107596,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/dw_apb_timer_of.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate",
        "drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate"
      ]
    },
    {
      "addr": 3234107952,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/timer-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe"
      ]
    },
    {
      "addr": 3234109032,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/timer-armada-370-xp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_timer_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_375_timer_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_375_timer_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_xp_timer_init"
      ]
    },
    {
      "addr": 3243948000,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/timer-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-orion.c:orion_timer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243950276,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/exynos_mct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/exynos_mct.c:mct_init_dt"
      ],
      "caller_func": []
    },
    {
      "addr": 3243956476,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/arm_global_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3234119944,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/timer-imx-gpt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init",
        "drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init"
      ]
    },
    {
      "addr": 3243959820,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/timer-imx-tpm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-imx-tpm.c:tpm_timer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3234203864,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mailbox/rockchip-mailbox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234246476,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/devfreq/exynos-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/exynos-bus.c:exynos_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234249000,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/devfreq/event/exynos-nocp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234252420,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/devfreq/event/exynos-ppmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234276600,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/memory/mvebu-devbus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/mvebu-devbus.c:mvebu_devbus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234279908,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/memory/mtk-smi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/mtk-smi.c:mtk_smi_common_resume",
        "drivers/memory/mtk-smi.c:mtk_smi_common_resume",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_resume",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3234495296,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "sound/soc/soc-dapm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234588768,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "sound/soc/codecs/sgtl5000.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234597696,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "sound/soc/fsl/fsl_ssi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params"
      ],
      "caller_func": []
    },
    {
      "addr": 3234601820,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "sound/soc/fsl/imx-audmux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/fsl/imx-audmux.c:imx_audmux_resume",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_resume",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_suspend",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_suspend",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port",
        "sound/soc/fsl/imx-audmux.c:audmux_read_file",
        "sound/soc/fsl/imx-audmux.c:audmux_read_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224574232,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 3230655532,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3230656128,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3230656364,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3230656424,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3230656484,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3230669300,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3230669360,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3230770636,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3234107596,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3234107952,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3234109032,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3234119944,
      "name": "clk_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290853592,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291146420,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
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
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_of.c:of_serial_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291846744,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291854156,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292431276,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292460376,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292551280,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
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
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294335244,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275507640,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275525776,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pwm/pwm-sifive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/pwm-sifive.c:pwm_sifive_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275735290,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/pci-ftpci100.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275873912,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/video/fbdev/simplefb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276208994,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276213698,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276222502,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276509066,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276532012,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276575430,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277005170,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/spi/spi-sifive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-sifive.c:sifive_spi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277258540,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277666090,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270836268,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/clocksource/timer-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-of.c:timer_of_init"
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
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584769589,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pci-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585642219,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585650145,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586162765,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586166885,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586966876,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587088220,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587115822,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
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
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584700373,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pci-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585507291,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585515217,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585982045,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585986165,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
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
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584771013,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/pci/controller/dwc/pci-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831627,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585839553,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586348157,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586361285,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586409143,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587215356,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587336700,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364302,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587664316,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_prepare_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585939243,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585947169,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586459837,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586472965,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586520823,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587322124,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587443180,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587470654,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587770700,
      "name": "clk_prepare_enable",
      "external": false,
      "loc": "include/linux/clk.h:903",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int clk_prepare_enable(struct clk * clk)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int clk_prepare_enable(struct clk * clk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int clk_prepare_enable(struct clk * clk)
```
</details>
</li>
</ul>

# Function: <code>clk_disable_unprepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584140217,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:482",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584585662,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:482",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584653980,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:482",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585273868,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:482",
      "file": "drivers/usb/phy/phy-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585293119,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:482",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585386972,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:482",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585415340,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:482",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
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
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584476914,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:498",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584934014,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:498",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585001868,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:498",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679199,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:498",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585783292,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:498",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585811324,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:498",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
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
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584659005,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:522",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585117406,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:522",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585128085,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:522",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585185324,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:522",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585860914,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:522",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585972028,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:522",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585999996,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:522",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
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
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584741314,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585198750,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585209536,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585267507,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585947285,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586055785,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586083417,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586345109,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585156808,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585169951,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585626910,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585637680,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585695603,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586390408,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586500201,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586527897,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586809573,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:654",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585167920,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585390932,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:716",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585405999,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:716",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585871246,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:716",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585881995,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:716",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585941501,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:716",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586650760,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:716",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764667,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:716",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586791867,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:716",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587077733,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:716",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585403152,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584485327,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:837",
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
      "addr": 18446744071585514388,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585529231,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586007022,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586017771,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586077677,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586802520,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586922219,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586949003,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587238005,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:837",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584483392,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585526640,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584682363,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:915",
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
      "addr": 18446744071585741084,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:915",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585747581,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:915",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586250802,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:915",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586261471,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:915",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586312662,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:915",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587060680,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:915",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587181835,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:915",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587209403,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:915",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587505083,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:915",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681008,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585745296,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585883324,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585889821,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586399010,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586409695,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586460838,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587261048,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587382059,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587409659,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587708219,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585887536,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586612329,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:921",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586627264,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:921",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587174610,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:921",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587185423,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:921",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587238337,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:921",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115096,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:921",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588241291,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:921",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588269467,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:921",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588577979,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:921",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586619904,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591390306,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:939",
      "file": "drivers/gpio/gpio-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-xilinx.c:xgpio_probe",
        "drivers/gpio/gpio-xilinx.c:xgpio_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586722249,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:939",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586736800,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:939",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587258146,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:939",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587268287,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:939",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587307793,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:939",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588156141,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:939",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588277051,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:939",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304587,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:939",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588602043,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:939",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586729552,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591387345,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586605673,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586620416,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587025964,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587146642,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587156511,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587194238,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588037968,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588160139,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588187835,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588486155,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586613104,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592428104,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587148857,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587163040,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587593260,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587722247,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587756163,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588659168,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588663311,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588798603,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588827835,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589154587,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587159776,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594296313,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588458080,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588473963,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588930030,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589066391,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589101152,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590075721,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590080370,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590221675,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590252331,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590607004,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:961",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588470496,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589276336,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/clk/clk-devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589373813,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589895259,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589908093,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590443598,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590596195,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590636940,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591683689,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591688738,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591839835,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591872507,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592267164,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589276336,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589904736,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589572928,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/clk/clk-devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589672444,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590204481,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590763294,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590978317,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592106651,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592112140,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592262763,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592295915,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592692476,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589572928,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589882368,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/clk/clk-devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589983148,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590545303,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591105534,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591322285,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592847083,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592852572,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593003851,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593037227,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593438124,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:1083",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589882368,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496437852,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/irqchip/irq-imx-irqsteer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_suspend",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_remove",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496469332,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/bus/imx-weim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/imx-weim.c:weim_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496469568,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/bus/qcom-ebi2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496488696,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/phy/phy-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-xgene.c:xgene_phy_hw_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496586864,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496670920,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pinctrl/sunxi/pinctrl-sunxi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496766872,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/gpio/gpio-davinci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496768656,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496784716,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/gpio/gpio-mxc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497110500,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/pcie-rcar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497139140,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/pcie-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497147040,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/pcie-mediatek.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497171984,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/dwc/pci-imx6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497189208,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/dwc/pcie-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497191832,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/dwc/pcie-armada8k.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497192788,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/dwc/pcie-kirin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497195168,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/dwc/pcie-histb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497369008,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/video/fbdev/simplefb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497730044,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511150332,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/imx/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk.c:imx_clk_disable_uart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497936256,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/renesas/rcar-usb2-clock-sel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497949680,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/rockchip/clk-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497969072,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/sunxi/clk-sun9i-mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497970044,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/sunxi/clk-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert",
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497995304,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/sunxi-ng/ccu-sun8i-de2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498053760,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_xor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498054228,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/dma/mv_xor_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_remove",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511189116,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/dma/mxs-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498073428,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_idmac.c:ipu_remove",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498077632,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/bcm/bcm2835-power.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_off",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498119276,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/imx/gpcv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498124192,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/mediatek/mtk-scpsys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498126300,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/amlogic/meson-gx-pwrc-vpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498613248,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/8250/8250_dw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_suspend",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_suspend",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_remove",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_remove",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498618424,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498622068,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_of.c:of_serial_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498634988,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498648252,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498651100,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_thaw",
        "drivers/tty/serial/imx.c:imx_uart_resume",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498669200,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
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
      "addr": 18446603336498676576,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498684292,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:msm_shutdown",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498915088,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/iommu/qcom_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/qcom_iommu.c:qcom_iommu_suspend",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_suspend",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499245008,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499271276,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499328848,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499817992,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/ata/ahci_imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ahci_imx.c:ahci_imx_host_stop",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_sata_disable",
        "drivers/ata/ahci_imx.c:imx_sata_disable",
        "drivers/ata/ahci_imx.c:imx_sata_disable",
        "drivers/ata/ahci_imx.c:imx_sata_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499842484,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/ata/libahci_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libahci_platform.c:ahci_platform_disable_clks",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_clks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499956520,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/net/phy/mdio-mux-bcm-iproc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_suspend",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_remove",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500011268,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500350108,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/phy/phy-mxs-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500372036,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500505296,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ehci-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_remove",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511367592,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/rtc/rtc-mv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-mv.c:mv_rtc_remove",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500825344,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/rtc/rtc-rtd119x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_remove",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500831076,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/rtc/rtc-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-xgene.c:xgene_rtc_suspend",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_remove",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500873780,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500889720,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/i2c/busses/i2c-sprd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_runtime_suspend",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501041488,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/watchdog/rtd119x_wdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/rtd119x_wdt.c:rtd119x_clk_disable_unprepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501453956,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_runtime_suspend",
        "drivers/mmc/host/mmci.c:mmci_remove",
        "drivers/mmc/host/mmci.c:mmci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501488496,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/firmware/qcom_scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable",
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable",
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511291340,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clocksource/timer-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-of.c:timer_of_cleanup",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/timer-of.c:timer_of_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511292072,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clocksource/timer-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-rockchip.c:rk_timer_cleanup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_cleanup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501738172,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/memory/mtk-smi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498668248,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336498674648,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243299920,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "arch/arm/mach-mvebu/mvebu-soc-id.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224594284,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "arch/arm/mach-omap2/display.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/display.c:omap_dss_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3229757184,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/irqchip/irq-imx-irqsteer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_suspend",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_remove",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229763916,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/bus/imx-weim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/imx-weim.c:weim_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229771176,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/bus/qcom-ebi2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229793944,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/phy/marvell/phy-mvebu-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 3229797240,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/phy/samsung/phy-exynos5250-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229863556,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pinctrl/pinctrl-rzn1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_remove",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229901996,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230041024,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230055920,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/gpio/gpio-mxc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230087100,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/gpio/gpio-vf610.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-vf610.c:vf610_gpio_disable_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 3230310284,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/pci-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230322428,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/pci-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off"
      ],
      "caller_func": []
    },
    {
      "addr": 3230331420,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/pcie-rcar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230350468,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/pcie-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3230359928,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/pcie-mediatek.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_subsys_powerdown"
      ],
      "caller_func": []
    },
    {
      "addr": 3230379024,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/dwc/pci-imx6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3230391360,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/dwc/pcie-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0"
      ],
      "caller_func": []
    },
    {
      "addr": 3230392760,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/dwc/pcie-armada8k.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230393648,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/dwc/pcie-histb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230396592,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pci/controller/dwc/pcie-uniphier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_remove",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230545776,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/video/fbdev/simplefb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230552456,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_put_disable_pclk"
      ],
      "caller_func": []
    },
    {
      "addr": 3243605652,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/imx/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk.c:imx_clk_disable_uart"
      ],
      "caller_func": []
    },
    {
      "addr": 3243626412,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/imx/clk-imx5.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx50_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230682436,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/renesas/rcar-usb2-clock-sel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230696316,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/rockchip/clk-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk"
      ],
      "caller_func": []
    },
    {
      "addr": 3230740060,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/tegra/clk-emc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-emc.c:emc_set_timing"
      ],
      "caller_func": []
    },
    {
      "addr": 3243825740,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clk/ti/clk-3xxx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5",
        "drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5"
      ],
      "caller_func": []
    },
    {
      "addr": 3230818572,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_xor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3243829916,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/dma/mxs-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 3230832264,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_idmac.c:ipu_remove",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230834236,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/dma/tegra20-apb-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3230876512,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/imx/gpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/imx/gpc.c:imx6_pm_domain_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 3230879496,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/imx/gpcv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req"
      ],
      "caller_func": []
    },
    {
      "addr": 3230883440,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/mediatek/mtk-scpsys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 3230886620,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/amlogic/meson-gx-pwrc-vpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230901560,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/tegra/fuse/fuse-tegra30.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3230902504,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/tegra/fuse/fuse-tegra20.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3230904344,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/soc/tegra/pmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/pmc.c:tegra_powergate_enable_clocks",
        "drivers/soc/tegra/pmc.c:tegra_powergate_disable_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3231012000,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/regulator/fixed.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/fixed.c:reg_clock_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3231241224,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231244800,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_of.c:of_serial_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3231261204,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 3231264964,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231272540,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_thaw",
        "drivers/tty/serial/imx.c:imx_uart_resume",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 3231290104,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
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
      "addr": 3231293720,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231300196,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:msm_shutdown",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 3231486132,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/iommu/exynos-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3231495208,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/iommu/qcom_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/qcom_iommu.c:qcom_iommu_suspend",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_suspend",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3231749892,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231785876,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/t7l66xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/t7l66xb.c:t7l66xb_remove",
        "drivers/mfd/t7l66xb.c:t7l66xb_remove",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_suspend",
        "drivers/mfd/t7l66xb.c:t7l66xb_mmc_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3231787868,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/tc6387xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc6387xb.c:tc6387xb_remove",
        "drivers/mfd/tc6387xb.c:tc6387xb_mmc_disable",
        "drivers/mfd/tc6387xb.c:tc6387xb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231789912,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/tc6393xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc6393xb.c:tc6393xb_suspend",
        "drivers/mfd/tc6393xb.c:tc6393xb_remove",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231795024,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3231878816,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3231926448,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/omap-usb-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232267064,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/ata/libahci_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libahci_platform.c:ahci_platform_disable_clks",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_clks"
      ],
      "caller_func": []
    },
    {
      "addr": 3232274780,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/ata/ahci_imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/ata/ahci_imx.c:imx8_sata_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3232535900,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232807700,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/phy/phy-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-generic.c:nop_set_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232811088,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/phy/phy-mxs-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 3232829016,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3232955980,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ehci-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_remove",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232958728,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ehci-exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_resume",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_suspend",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_remove",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232991552,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ohci-exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_resume",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_suspend",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_remove",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232996084,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_remove",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3244035028,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/rtc/rtc-mv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-mv.c:mv_rtc_remove",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233334232,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/rtc/rtc-omap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-omap.c:omap_rtc_remove",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233345540,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/rtc/rtc-s3c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233382688,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233399696,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/i2c/busses/i2c-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_remove",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233537856,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/thermal/samsung/exynos_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_remove",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233810820,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/cpufreq/tegra20-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_cpu_exit",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_target",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_target_intermediate"
      ],
      "caller_func": []
    },
    {
      "addr": 3233939912,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_runtime_suspend",
        "drivers/mmc/host/mmci.c:mmci_remove",
        "drivers/mmc/host/mmci.c:mmci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233982744,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mmc/host/omap_hsmmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios"
      ],
      "caller_func": []
    },
    {
      "addr": 3233992932,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mmc/host/sdhci-pltfm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_resume",
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_suspend",
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 3234001444,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mmc/host/sdhci-esdhc-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234026612,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/firmware/qcom_scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable",
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable",
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3243943364,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clocksource/timer-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-of.c:timer_of_cleanup",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/timer-of.c:timer_of_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243944192,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clocksource/renesas-ostm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/renesas-ostm.c:ostm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243945772,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clocksource/timer-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-rockchip.c:rk_timer_cleanup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_cleanup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3243956584,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clocksource/arm_global_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3234247396,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/devfreq/exynos-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/exynos-bus.c:exynos_bus_probe",
        "drivers/devfreq/exynos-bus.c:exynos_bus_probe",
        "drivers/devfreq/exynos-bus.c:exynos_bus_passive_exit",
        "drivers/devfreq/exynos-bus.c:exynos_bus_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 3234247700,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/devfreq/event/exynos-nocp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/event/exynos-nocp.c:exynos_nocp_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3234249236,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/devfreq/event/exynos-ppmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3234277976,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/memory/mtk-smi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3234495276,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "sound/soc/soc-dapm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234586508,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "sound/soc/codecs/sgtl5000.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_remove",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234597908,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "sound/soc/fsl/fsl_ssi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_free",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 3234601900,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "sound/soc/fsl/imx-audmux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/fsl/imx-audmux.c:imx_audmux_resume",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_suspend",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port",
        "sound/soc/fsl/imx-audmux.c:audmux_read_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231288252,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3231291604,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290853264,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291841864,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_of.c:of_serial_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291846456,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291854196,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292428416,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292460632,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292550832,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293689912,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291853728,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275506054,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275524628,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/pwm/pwm-sifive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/pwm-sifive.c:pwm_sifive_remove",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275873208,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/video/fbdev/simplefb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276208178,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276211818,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276223094,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276506900,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276527662,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276575132,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277004906,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/spi/spi-sifive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-sifive.c:sifive_spi_remove",
        "drivers/spi/spi-sifive.c:sifive_spi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277258720,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277666140,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270836810,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/clocksource/timer-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-of.c:timer_of_cleanup",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/timer-of.c:timer_of_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276222130,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584769643,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
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
      "addr": 18446744071585644316,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585650813,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586161586,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586163263,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586967128,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587088139,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587115739,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584768288,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585648528,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584700427,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
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
      "addr": 18446744071585509388,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585515885,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585980866,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585982543,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584699072,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585513600,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584771067,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
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
      "addr": 18446744071585833724,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585840221,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586346978,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586357663,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586408806,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587215608,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587336619,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364219,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587664363,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769712,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585837936,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```

```json
{
  "name": "clk_disable_unprepare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585941340,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585947837,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586458658,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586469343,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586520486,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587322376,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587443099,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587470571,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587770747,
      "name": "clk_disable_unprepare",
      "external": false,
      "loc": "include/linux/clk.h:918",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585945552,
      "name": "clk_disable_unprepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void clk_disable_unprepare(struct clk * clk)
```
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct clk * clk</code> ➡️ <code>struct clk * clk</code>
</li>
</ul>
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

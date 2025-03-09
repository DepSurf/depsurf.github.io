# Function: <code>reset_control_assert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953536,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:106",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953536,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584286080,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:162",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286080,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584467712,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:186",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467712,
      "name": "reset_control_assert",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584552400,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:197",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552400,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584963248,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:272",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584963248,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585196032,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:302",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585196032,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585314624,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:302",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314624,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585527091,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:342",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527926,
      "name": "reset_control_assert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585527040,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585668160,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:341",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668160,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586394224,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:343",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586394224,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586509360,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:417",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586509360,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586394608,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:441",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/reset/core.c:reset_control_bulk_deassert",
        "drivers/reset/core.c:reset_control_bulk_assert",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586394608,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586920818,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:441",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/reset/core.c:reset_control_bulk_deassert",
        "drivers/reset/core.c:reset_control_bulk_assert",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592445590,
      "name": "reset_control_assert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071586920752,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:442",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/reset/core.c:reset_control_bulk_deassert",
        "drivers/reset/core.c:reset_control_deassert",
        "drivers/reset/core.c:reset_control_bulk_assert",
        "drivers/reset/core.c:reset_control_assert",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594313637,
      "name": "reset_control_assert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071588214560,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:442",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/reset/core.c:reset_control_bulk_deassert",
        "drivers/reset/core.c:reset_control_deassert",
        "drivers/reset/core.c:reset_control_bulk_assert",
        "drivers/reset/core.c:reset_control_assert",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596232459,
      "name": "reset_control_assert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589622864,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:442",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/reset/core.c:reset_control_bulk_deassert",
        "drivers/reset/core.c:reset_control_deassert",
        "drivers/reset/core.c:reset_control_bulk_assert",
        "drivers/reset/core.c:reset_control_assert",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596760368,
      "name": "reset_control_assert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589926400,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:442",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/reset/core.c:reset_control_bulk_deassert",
        "drivers/reset/core.c:reset_control_deassert",
        "drivers/reset/core.c:reset_control_bulk_assert",
        "drivers/reset/core.c:reset_control_assert",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597668919,
      "name": "reset_control_assert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071590264688,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498335816,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:341",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sunxi/pinctrl-sun6i-a31-r.c:sun6i_a31_r_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a23-r.c:sun8i_a23_r_pinctrl_probe",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_remove",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_resources",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_pwrreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498335816,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231028420,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:341",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary",
        "arch/arm/mach-meson/platsmp.c:meson8_smp_boot_secondary",
        "arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain",
        "drivers/bus/ti-sysc.c:sysc_remove",
        "drivers/bus/ti-sysc.c:sysc_probe",
        "drivers/bus/ti-sysc.c:sysc_init_module",
        "drivers/bus/ti-sysc.c:sysc_runtime_suspend",
        "drivers/bus/ti-sysc.c:sysc_runtime_suspend",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_remove",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_remove",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on",
        "drivers/soc/tegra/pmc.c:tegra_powergate_init",
        "drivers/soc/tegra/pmc.c:tegra_genpd_power_off",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_resources",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_pwrreg",
        "drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231028420,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291516368,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:341",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291516368,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276023184,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:341",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276023184,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585429184,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:341",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585429184,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585299232,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:341",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585299232,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585618560,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:341",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618560,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int reset_control_assert(struct reset_control * rstc)
```

```json
{
  "name": "reset_control_assert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585726688,
      "name": "reset_control_assert",
      "external": true,
      "loc": "drivers/reset/core.c:341",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585726688,
      "name": "reset_control_assert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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

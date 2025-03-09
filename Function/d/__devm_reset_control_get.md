# Function: <code>__devm_reset_control_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, int shared)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584285712,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:340",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584285712,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, int shared)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584467424,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:381",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467424,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584551984,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:427",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584551984,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584962304,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:542",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584962304,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585197008,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:636",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585197008,
      "name": "__devm_reset_control_get",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585313728,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:637",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585313728,
      "name": "__devm_reset_control_get",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585526576,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:778",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585526576,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667664,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:778",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667664,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586392912,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:779",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586392912,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586508048,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:853",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586508048,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586392528,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:1033",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586392528,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919120,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:1034",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919120,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588212064,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:1035",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588212064,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589620192,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:1035",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589620192,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589923712,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:1035",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589923712,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590262256,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:1035",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590262256,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498333680,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:778",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sunxi/pinctrl-sun6i-a31-r.c:sun6i_a31_r_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a23-r.c:sun8i_a23_r_pinctrl_probe",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/host/mmci.c:mmci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498333680,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231025960,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:778",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/ti-sysc.c:sysc_probe",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/host/mmci.c:mmci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231025960,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291520752,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:778",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291520752,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276021168,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:778",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276021168,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585428688,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:778",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585428688,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585298736,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:778",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298736,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618064,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:778",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618064,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__devm_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585726192,
      "name": "__devm_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:778",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585726192,
      "name": "__devm_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct reset_control * __devm_reset_control_get(struct device * dev, const char * id, int index, int shared)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool optional</code>
</li>
<li>
<b>Param type changed. </b>
<code>int shared</code> ➡️ <code>bool shared</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool acquired</code>
</li>
</ul>
</details>
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

# Function: <code>platform_get_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584405504,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:87",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpio-zx.c:zx_gpio_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584405504,
      "name": "platform_get_irq",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584740880,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:87",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpio-zx.c:zx_gpio_probe",
        "drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/platform.c:platform_irq_count",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584740880,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584930832,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:87",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/platform.c:platform_irq_count",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930832,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585015360,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:87",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:platform_irq_count",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015360,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437664,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:87",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:platform_irq_count",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437664,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585680800,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:86",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:platform_irq_count",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680800,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585810928,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:87",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:platform_irq_count",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810928,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586044256,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:107",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:platform_irq_count",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044256,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:165",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586196362,
      "name": "platform_get_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586192224,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:246",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_remove",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/gpio/gpio-msic.c:platform_msic_gpio_probe",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959211,
      "name": "platform_get_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586957808,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587043857,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:277",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/gpio/gpio-msic.c:platform_msic_gpio_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591486864,
      "name": "platform_get_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587043568,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586927686,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:276",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430564,
      "name": "platform_get_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586927392,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587489597,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:256",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592489760,
      "name": "platform_get_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587489296,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588812200,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:259",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_mmio.c:vm_synchronize_cbs",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588811856,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590310184,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:259",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_mmio.c:vm_synchronize_cbs",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590309824,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590630680,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:259",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_mmio.c:vm_synchronize_cbs",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590630320,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590989912,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:260",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_mmio.c:vm_synchronize_cbs",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590989552,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498994472,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:165",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_probe",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_probe",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_filter_fn",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe",
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe",
        "drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/amba-pl011.c:sbsa_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/msm_serial.c:msm_serial_probe",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe",
        "drivers/tty/serial/owl-uart.c:owl_uart_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_shutdown",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_init_host",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_resume",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_suspend",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/edac/altera_edac.c:altr_edac_a10_probe",
        "drivers/edac/altera_edac.c:altr_edac_device_probe",
        "drivers/edac/altera_edac.c:altr_edac_device_probe",
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe",
        "drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_probe",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm_pmu_platform.c:pmu_parse_irqs",
        "drivers/perf/arm_pmu_platform.c:pmu_parse_irqs",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498994472,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231562724,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:165",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/bus/omap_l3_smx.c:omap3_l3_probe",
        "drivers/bus/omap_l3_smx.c:omap3_l3_probe",
        "drivers/bus/omap_l3_noc.c:omap_l3_probe",
        "drivers/bus/omap_l3_noc.c:omap_l3_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_probe",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_probe",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_probe",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_filter_fn",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/ti/omap-dma.c:omap_dma_remove",
        "drivers/dma/ti/omap-dma.c:omap_dma_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/amba-pl011.c:sbsa_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/msm_serial.c:msm_serial_probe",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe",
        "drivers/tty/serial/owl-uart.c:owl_uart_probe",
        "drivers/tty/serial/rda-uart.c:rda_uart_probe",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_probe",
        "drivers/iommu/omap-iommu.c:omap_iommu_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_shutdown",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe",
        "drivers/mfd/sm501.c:sm501_plat_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/tc6387xb.c:tc6387xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_init_host",
        "drivers/ata/sata_highbank.c:ahci_highbank_probe",
        "drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip",
        "drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/auxdisplay/arm-charlcd.c:charlcd_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-twl.c:twl_rtc_probe",
        "drivers/rtc/rtc-twl.c:twl_rtc_alarm_irq_enable",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/watchdog/npcm_wdt.c:npcm_wdt_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/em_sti.c:em_sti_probe",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe",
        "drivers/memory/tegra/mc.c:tegra_mc_probe",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe",
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231562724,
      "name": "platform_get_irq",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292150400,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:165",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292150400,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276369072,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:165",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sifive.c:sifive_serial_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276369072,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:165",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585956570,
      "name": "platform_get_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585952432,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:165",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805786,
      "name": "platform_get_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585801648,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:165",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586146378,
      "name": "platform_get_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586142240,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int platform_get_irq(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_get_irq",
      "external": true,
      "loc": "drivers/base/platform.c:165",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255082,
      "name": "platform_get_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586250928,
      "name": "platform_get_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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

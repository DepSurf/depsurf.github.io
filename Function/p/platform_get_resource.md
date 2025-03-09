# Function: <code>platform_get_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584404800,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:67",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-zx.c:zx_gpio_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404800,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584740885,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:67",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-zx.c:zx_gpio_probe",
        "drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584740144,
      "name": "platform_get_resource",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584930837,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:67",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930096,
      "name": "platform_get_resource",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585015365,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:67",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585014672,
      "name": "platform_get_resource",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585437676,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:67",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436928,
      "name": "platform_get_resource",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585680805,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:66",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680064,
      "name": "platform_get_resource",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585810933,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:67",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810288,
      "name": "platform_get_resource",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586044261,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:67",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043504,
      "name": "platform_get_resource",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586191893,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:49",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586191136,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586957349,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:49",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:devm_platform_ioremap_resource_wc",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/intel_msic.c:intel_msic_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952928,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587041874,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:53",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:devm_platform_ioremap_resource_wc",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/intel_msic.c:intel_msic_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037904,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586925682,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:53",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:devm_platform_ioremap_resource_wc",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586921728,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587487826,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:53",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/viot.c:viot_iommu_configure",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587484128,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588810318,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:55",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/viot.c:viot_iommu_configure",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588806128,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590308334,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:55",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/acpi/viot.c:viot_iommu_configure",
        "drivers/reset/reset-simple.c:reset_simple_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590303536,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590628830,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:55",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/acpi/viot.c:viot_iommu_configure",
        "drivers/reset/reset-simple.c:reset_simple_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590623936,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590988050,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:55",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/acpi/viot.c:viot_iommu_configure",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590983184,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498991020,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:49",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/irqchip/irq-mbigen.c:mbigen_device_probe",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe",
        "drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe",
        "drivers/irqchip/irq-sni-exiu.c:exiu_acpi_probe",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe",
        "drivers/bus/hisi_lpc.c:hisi_lpc_probe",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/bus/imx-weim.c:weim_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/phy/phy-xgene.c:xgene_phy_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe",
        "drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe",
        "drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_mmio_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_platform_init",
        "drivers/pci/controller/pci-thunder-pem.c:thunder_pem_platform_init",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe",
        "drivers/clk/actions/owl-common.c:owl_clk_regmap_init",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe",
        "drivers/clk/bcm/clk-bcm2835-aux.c:bcm2835_aux_clk_probe",
        "drivers/clk/hisilicon/clk.c:hisi_clk_alloc",
        "drivers/clk/hisilicon/reset.c:hisi_reset_init",
        "drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_probe",
        "drivers/clk/imx/clk-imx8qxp-lpcg.c:imx8qxp_lpcg_clk_probe",
        "drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_top_probe",
        "drivers/clk/mediatek/clk-mt6797.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_mcu_probe",
        "drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_top_probe",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_mcu_probe",
        "drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_top_probe",
        "drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe",
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe",
        "drivers/clk/socfpga/clk-s10.c:s10_clkmgr_init",
        "drivers/clk/sunxi/clk-mod0.c:sun4i_a10_mod0_clk_probe",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe",
        "drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_clk_probe",
        "drivers/clk/sunxi/clk-sun6i-apb0.c:sun6i_a31_apb0_clk_probe",
        "drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe",
        "drivers/clk/sunxi/clk-sun6i-ar100.c:sun6i_a31_ar100_clk_probe",
        "drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-a83t.c:sun8i_a83t_ccu_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe",
        "drivers/soc/fsl/guts.c:fsl_guts_probe",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe",
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/reset/reset-meson.c:meson_reset_probe",
        "drivers/reset/reset-qcom-aoss.c:qcom_aoss_reset_probe",
        "drivers/reset/reset-simple.c:reset_simple_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/tty/serial/amba-pl011.c:sbsa_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/msm_serial.c:msm_serial_probe",
        "drivers/tty/serial/msm_serial.c:msm_request_port",
        "drivers/tty/serial/msm_serial.c:msm_release_port",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe",
        "drivers/tty/serial/owl-uart.c:owl_uart_probe",
        "drivers/tty/serial/owl-uart.c:owl_uart_request_port",
        "drivers/tty/serial/owl-uart.c:owl_uart_release_port",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_probe",
        "drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe",
        "drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/sun6i-prcm.c:sun6i_prcm_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe",
        "drivers/mfd/altera-sysmgr.c:sysmgr_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_init_host",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs_len",
        "drivers/net/ethernet/freescale/fman/fman.c:read_dts_node",
        "drivers/net/ethernet/freescale/fman/fman.c:read_dts_node",
        "drivers/net/ethernet/freescale/fman/fman.c:read_dts_node",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_remove",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/power/reset/msm-poweroff.c:msm_restart_probe",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/edac/altera_edac.c:altr_edac_device_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe",
        "drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_probe",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498990512,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231559508,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:49",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev",
        "fs/pstore/ram.c:ramoops_probe",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/bus/imx-weim.c:weim_probe",
        "drivers/bus/omap_l3_smx.c:omap3_l3_probe",
        "drivers/bus/omap_l3_noc.c:omap_l3_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_probe",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_probe",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos_pcie_phy_probe",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos_pcie_phy_probe",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_resume",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_suspend",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe",
        "drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_mmio_probe",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init",
        "drivers/gpio/gpio-htc-egpio.c:egpio_probe",
        "drivers/gpio/gpio-htc-egpio.c:egpio_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_probe",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/video/fbdev/omap2/omapfb/vrfb.c:vrfb_probe",
        "drivers/video/fbdev/omap2/omapfb/vrfb.c:vrfb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/amba/tegra-ahb.c:tegra_ahb_probe",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe",
        "drivers/clk/clk-milbeaut.c:m10v_clk_probe",
        "drivers/clk/actions/owl-common.c:owl_clk_regmap_init",
        "drivers/clk/hisilicon/clk.c:hisi_clk_alloc",
        "drivers/clk/hisilicon/reset.c:hisi_reset_init",
        "drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_probe",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/ti/adpll.c:ti_adpll_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/dma/ti/omap-dma.c:omap_dma_probe",
        "drivers/dma/ti/dma-crossbar.c:ti_dma_xbar_probe",
        "drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe",
        "drivers/soc/fsl/guts.c:fsl_guts_probe",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe",
        "drivers/soc/qcom/spm.c:spm_dev_probe",
        "drivers/soc/samsung/exynos-pmu.c:exynos_pmu_probe",
        "drivers/soc/tegra/fuse/fuse-tegra.c:tegra_fuse_probe",
        "drivers/soc/tegra/flowctrl.c:tegra_flowctrl_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/reset/reset-meson.c:meson_reset_probe",
        "drivers/reset/reset-qcom-aoss.c:qcom_aoss_reset_probe",
        "drivers/reset/reset-simple.c:reset_simple_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/tty/serial/amba-pl011.c:sbsa_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/msm_serial.c:msm_serial_probe",
        "drivers/tty/serial/msm_serial.c:msm_request_port",
        "drivers/tty/serial/msm_serial.c:msm_release_port",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe",
        "drivers/tty/serial/owl-uart.c:owl_uart_probe",
        "drivers/tty/serial/owl-uart.c:owl_uart_request_port",
        "drivers/tty/serial/owl-uart.c:owl_uart_release_port",
        "drivers/tty/serial/rda-uart.c:rda_uart_probe",
        "drivers/tty/serial/rda-uart.c:rda_uart_release_port",
        "drivers/tty/serial/rda-uart.c:rda_uart_request_port",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_probe",
        "drivers/iommu/omap-iommu.c:omap_iommu_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/tegra-gart.c:tegra_gart_probe",
        "drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_probe",
        "drivers/mfd/sm501.c:sm501_plat_probe",
        "drivers/mfd/sm501.c:sm501_plat_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/tc6387xb.c:tc6387xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe",
        "drivers/mfd/omap-usb-tll.c:usbtll_omap_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_init_host",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/ata/sata_highbank.c:ahci_highbank_probe",
        "drivers/mtd/nand/raw/omap2.c:omap_nand_probe",
        "drivers/mtd/nand/raw/omap_elm.c:elm_probe",
        "drivers/mtd/nand/raw/omap_elm.c:elm_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs_len",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/auxdisplay/arm-charlcd.c:charlcd_probe",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_remove",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_probe",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe",
        "drivers/usb/musb/musb_core.c:musb_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe",
        "drivers/power/avs/smartreflex.c:omap_sr_probe",
        "drivers/power/avs/smartreflex.c:omap_sr_probe",
        "drivers/power/reset/brcm-kona-reset.c:kona_reset_probe",
        "drivers/power/reset/msm-poweroff.c:msm_restart_probe",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/edac/armada_xp_edac.c:aurora_l2_probe",
        "drivers/edac/armada_xp_edac.c:axp_mc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/em_sti.c:em_sti_probe",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_probe",
        "drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe",
        "drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/mvebu-devbus.c:mvebu_devbus_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_probe",
        "drivers/memory/tegra/mc.c:tegra_mc_probe",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231558716,
      "name": "platform_get_resource",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292145372,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:49",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/soc/fsl/guts.c:fsl_guts_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292144736,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276365950,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:49",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe",
        "drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sifive.c:sifive_serial_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276365734,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585952101,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:49",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585951504,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585801317,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:49",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585800560,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586141909,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:49",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141152,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct resource * platform_get_resource(struct platform_device * dev, unsigned int type, unsigned int num)
```

```json
{
  "name": "platform_get_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586250597,
      "name": "platform_get_resource",
      "external": true,
      "loc": "drivers/base/platform.c:49",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:devm_platform_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/rtc/rtc-cmos.c:cmos_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586249840,
      "name": "platform_get_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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

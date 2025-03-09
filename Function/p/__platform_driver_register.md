# Function: <code>__platform_driver_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584407072,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:593",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/platform.c:__platform_register_drivers"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-zx.c:zx_gpio_driver_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/regulator/tps65217-regulator.c:tps65217_regulator_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_init",
        "drivers/usb/phy/phy-generic.c:usb_phy_generic_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/power/charger-manager.c:charger_manager_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407072,
      "name": "__platform_driver_register",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584743228,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:613",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-zx.c:zx_gpio_driver_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/power/charger-manager.c:charger_manager_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742448,
      "name": "__platform_driver_register",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584933244,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:627",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932464,
      "name": "__platform_driver_register",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585017596,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:627",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585016816,
      "name": "__platform_driver_register",
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
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585439916,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:627",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/pinctrl/intel/pinctrl-cannonlake.c:cnl_pinctrl_driver_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585439136,
      "name": "__platform_driver_register",
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
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585682732,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:625",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-st.c:st_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/i2c/busses/i2c-amd-platdrv.c:amd_i2c_plat_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585682240,
      "name": "__platform_driver_register",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585812892,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:627",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-st.c:st_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585812400,
      "name": "__platform_driver_register",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586046241,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:667",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/gpio/gpio-xilinx.c:xgpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-st.c:st_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045792,
      "name": "__platform_driver_register",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586194145,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:732",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/gpio/gpio-xilinx.c:xgpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-st.c:st_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586193696,
      "name": "__platform_driver_register",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586955121,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:793",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_init",
        "drivers/gpio/gpio-msic.c:platform_msic_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/gpio/gpio-xilinx.c:xgpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/evged.c:ged_driver_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_driver_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-st.c:st_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_driver_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/intel_msic.c:intel_msic_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954432,
      "name": "__platform_driver_register",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587039921,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:889",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_init",
        "drivers/gpio/gpio-msic.c:platform_msic_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/gpio/gpio-xilinx.c:xgpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/evged.c:ged_driver_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_driver_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-fch.c:fch_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_driver_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/intel_msic.c:intel_msic_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039504,
      "name": "__platform_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586923729,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:888",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/evged.c:ged_driver_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_driver_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-fch.c:fch_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923312,
      "name": "__platform_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587485374,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:852",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/acpi/evged.c:ged_driver_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_driver_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-fch.c:fch_clk_driver_init",
        "drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/reset/tps65086-restart.c:tps65086_restart_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587484960,
      "name": "__platform_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588807550,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:861",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-mmio.c:bgpio_driver_init",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/acpi/evged.c:ged_driver_init",
        "drivers/acpi/fan_core.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:acpi_ghes_init",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_driver_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-fch.c:fch_clk_driver_init",
        "drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/reset/tps65086-restart.c:tps65086_restart_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588807088,
      "name": "__platform_driver_register",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590305248,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:861",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-mmio.c:bgpio_driver_init",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/acpi/evged.c:ged_driver_init",
        "drivers/acpi/fan_core.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:acpi_ghes_init",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_driver_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-fch.c:fch_clk_driver_init",
        "drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/reset/reset-simple.c:reset_simple_driver_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/reset/tps65086-restart.c:tps65086_restart_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_driver_init",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590304672,
      "name": "__platform_driver_register",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590625408,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:861",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-mmio.c:bgpio_driver_init",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/acpi/evged.c:ged_driver_init",
        "drivers/acpi/fan_core.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:acpi_ghes_init",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_driver_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-fch.c:fch_clk_driver_init",
        "drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/reset/reset-simple.c:reset_simple_driver_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/reset/tps65086-restart.c:tps65086_restart_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_driver_init",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590625120,
      "name": "__platform_driver_register",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590984656,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:861",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-mmio.c:bgpio_driver_init",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/acpi/evged.c:ged_driver_init",
        "drivers/acpi/ac.c:acpi_ac_init",
        "drivers/acpi/fan_core.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:acpi_ghes_init",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_driver_init",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_driver_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-fch.c:fch_clk_driver_init",
        "drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_driver_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/reset/reset-simple.c:reset_simple_driver_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/gpu/drm/tiny/simpledrm.c:simpledrm_platform_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/reset/tps65086-restart.c:tps65086_restart_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590984368,
      "name": "__platform_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498993424,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:732",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "arch/arm64/kernel/perf_event.c:armv8_pmu_driver_init",
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/irqchip/irq-mbigen.c:mbigen_platform_driver_init",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_init",
        "drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_driver_init",
        "drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_driver_init",
        "drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_subset_driver_init",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_driver_init",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_driver_init",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_driver_init",
        "drivers/irqchip/qcom-irq-combiner.c:qcom_irq_combiner_probe_init",
        "drivers/irqchip/irq-sni-exiu.c:exiu_driver_init",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_driver_init",
        "drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_driver_init",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_driver_init",
        "drivers/bus/arm-cci.c:cci_platform_init",
        "drivers/bus/hisi_lpc.c:hisi_lpc_driver_init",
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_driver_init",
        "drivers/bus/imx-weim.c:weim_driver_init",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_driver_init",
        "drivers/bus/sun50i-de2.c:sun50i_de2_bus_driver_init",
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_driver_init",
        "drivers/phy/phy-xgene.c:xgene_phy_driver_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_driver_init",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_driver_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinctrl_init",
        "drivers/pinctrl/meson/pinctrl-meson-gxbb.c:meson_gxbb_pinctrl_driver_init",
        "drivers/pinctrl/meson/pinctrl-meson-gxl.c:meson_gxl_pinctrl_driver_init",
        "drivers/pinctrl/meson/pinctrl-meson-axg.c:meson_axg_pinctrl_driver_init",
        "drivers/pinctrl/meson/pinctrl-meson-g12a.c:meson_g12a_pinctrl_driver_init",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_driver_init",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_drv_register",
        "drivers/pinctrl/pinctrl-single.c:pcs_driver_init",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_driver_init",
        "drivers/pinctrl/actions/pinctrl-s700.c:s700_pinctrl_init",
        "drivers/pinctrl/actions/pinctrl-s900.c:s900_pinctrl_init",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_driver_init",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_init",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_init",
        "drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_driver_init",
        "drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_driver_init",
        "drivers/pinctrl/freescale/pinctrl-imx8mm.c:imx8mm_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx8mn.c:imx8mn_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx8mq.c:imx8mq_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx8qm.c:imx8qm_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx8qxp.c:imx8qxp_pinctrl_init",
        "drivers/pinctrl/mvebu/pinctrl-armada-ap806.c:armada_ap806_pinctrl_driver_init",
        "drivers/pinctrl/mvebu/pinctrl-armada-cp110.c:armada_cp110_pinctrl_driver_init",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_init",
        "drivers/pinctrl/sprd/pinctrl-sprd-sc9860.c:sprd_pinctrl_init",
        "drivers/pinctrl/sunxi/pinctrl-sun4i-a10.c:sun4i_a10_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun5i.c:sun5i_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun6i-a31.c:sun6i_a31_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun6i-a31-r.c:sun6i_a31_r_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a23.c:sun8i_a23_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a23-r.c:sun8i_a23_r_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a33.c:sun8i_a33_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun50i-a64.c:a64_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun50i-a64-r.c:sun50i_a64_r_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a83t.c:sun8i_a83t_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a83t-r.c:sun8i_a83t_r_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-h3.c:sun8i_h3_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-h3-r.c:sun8i_h3_r_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-v3s.c:sun8i_v3s_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun50i-h5.c:sun50i_h5_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun50i-h6.c:h6_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun50i-h6-r.c:sun50i_h6_r_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun9i-a80.c:sun9i_a80_pinctrl_driver_init",
        "drivers/pinctrl/sunxi/pinctrl-sun9i-a80-r.c:sun9i_a80_r_pinctrl_driver_init",
        "drivers/pinctrl/mediatek/pinctrl-mt2712.c:mtk_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt6765.c:mt6765_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt6797.c:mt6797_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt7622.c:mt7622_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt8173.c:mtk_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt8183.c:mt8183_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt8516.c:mtk_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt6397.c:mtk_pinctrl_driver_init",
        "drivers/gpio/gpio-mmio.c:bgpio_driver_init",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_drv_reg",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_driver_init",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_init",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_driver_init",
        "drivers/gpio/gpio-mxc.c:gpio_mxc_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_init",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_driver_init",
        "drivers/gpio/gpio-xilinx.c:xgpio_init",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_driver_init",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_driver_init",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_driver_init",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_driver_init",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_driver_init",
        "drivers/pci/controller/pci-host-generic.c:gen_pci_driver_init",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_driver_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_driver_init",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_pcie_msi_init",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_driver_init",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_init",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_driver_init",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_driver_init",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_driver_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_driver_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_driver_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_driver_init",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_driver_init",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_platform_driver_init",
        "drivers/pci/controller/dwc/pcie-al.c:al_pcie_driver_init",
        "drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_almost_ecam_driver_init",
        "drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_driver_init",
        "drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_driver_init",
        "drivers/pci/controller/pci-thunder-pem.c:thunder_pem_driver_init",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/mx3fb.c:mx3fb_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/evged.c:ged_driver_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_driver_init",
        "drivers/clk/clk-fixed-rate.c:of_fixed_clk_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_driver_init",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_driver_init",
        "drivers/clk/actions/owl-s500.c:s500_clk_init",
        "drivers/clk/actions/owl-s700.c:s700_clk_init",
        "drivers/clk/actions/owl-s900.c:s900_clk_init",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_driver_init",
        "drivers/clk/bcm/clk-bcm2835-aux.c:bcm2835_aux_clk_driver_init",
        "drivers/clk/bcm/clk-sr.c:sr_clk_driver_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_init",
        "drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_init",
        "drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_init",
        "drivers/clk/imx/clk-imx8mm.c:imx8mm_clk_driver_init",
        "drivers/clk/imx/clk-imx8mn.c:imx8mn_clk_driver_init",
        "drivers/clk/imx/clk-imx8mq.c:imx8mq_clk_driver_init",
        "drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_driver_init",
        "drivers/clk/imx/clk-imx8qxp-lpcg.c:imx8qxp_lpcg_clk_driver_init",
        "drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_init",
        "drivers/clk/mediatek/clk-mt6779-mm.c:clk_mt6779_mm_drv_init",
        "drivers/clk/mediatek/clk-mt6779-img.c:clk_mt6779_img_drv_init",
        "drivers/clk/mediatek/clk-mt6779-ipe.c:clk_mt6779_ipe_drv_init",
        "drivers/clk/mediatek/clk-mt6779-cam.c:clk_mt6779_cam_drv_init",
        "drivers/clk/mediatek/clk-mt6779-vdec.c:clk_mt6779_vdec_drv_init",
        "drivers/clk/mediatek/clk-mt6779-venc.c:clk_mt6779_venc_drv_init",
        "drivers/clk/mediatek/clk-mt6779-mfg.c:clk_mt6779_mfg_drv_init",
        "drivers/clk/mediatek/clk-mt6779-aud.c:clk_mt6779_aud_drv_init",
        "drivers/clk/mediatek/clk-mt6797.c:clk_mt6797_init",
        "drivers/clk/mediatek/clk-mt6797-img.c:clk_mt6797_img_drv_init",
        "drivers/clk/mediatek/clk-mt6797-mm.c:clk_mt6797_mm_drv_init",
        "drivers/clk/mediatek/clk-mt6797-vdec.c:clk_mt6797_vdec_drv_init",
        "drivers/clk/mediatek/clk-mt6797-venc.c:clk_mt6797_venc_drv_init",
        "drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_init",
        "drivers/clk/mediatek/clk-mt2712-bdp.c:clk_mt2712_bdp_drv_init",
        "drivers/clk/mediatek/clk-mt2712-img.c:clk_mt2712_img_drv_init",
        "drivers/clk/mediatek/clk-mt2712-jpgdec.c:clk_mt2712_jpgdec_drv_init",
        "drivers/clk/mediatek/clk-mt2712-mfg.c:clk_mt2712_mfg_drv_init",
        "drivers/clk/mediatek/clk-mt2712-mm.c:clk_mt2712_mm_drv_init",
        "drivers/clk/mediatek/clk-mt2712-vdec.c:clk_mt2712_vdec_drv_init",
        "drivers/clk/mediatek/clk-mt2712-venc.c:clk_mt2712_venc_drv_init",
        "drivers/clk/mediatek/clk-mt7622.c:clk_mt7622_init",
        "drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_eth_drv_init",
        "drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_hif_drv_init",
        "drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_aud_drv_init",
        "drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_init",
        "drivers/clk/mediatek/clk-mt8183-audio.c:clk_mt8183_audio_drv_init",
        "drivers/clk/mediatek/clk-mt8183-cam.c:clk_mt8183_cam_drv_init",
        "drivers/clk/mediatek/clk-mt8183-img.c:clk_mt8183_img_drv_init",
        "drivers/clk/mediatek/clk-mt8183-ipu0.c:clk_mt8183_ipu_core0_drv_init",
        "drivers/clk/mediatek/clk-mt8183-ipu1.c:clk_mt8183_ipu_core1_drv_init",
        "drivers/clk/mediatek/clk-mt8183-ipu_adl.c:clk_mt8183_ipu_adl_drv_init",
        "drivers/clk/mediatek/clk-mt8183-ipu_conn.c:clk_mt8183_ipu_conn_drv_init",
        "drivers/clk/mediatek/clk-mt8183-mfgcfg.c:clk_mt8183_mfg_drv_init",
        "drivers/clk/mediatek/clk-mt8183-mm.c:clk_mt8183_mm_drv_init",
        "drivers/clk/mediatek/clk-mt8183-vdec.c:clk_mt8183_vdec_drv_init",
        "drivers/clk/mediatek/clk-mt8183-venc.c:clk_mt8183_venc_drv_init",
        "drivers/clk/meson/axg.c:axg_driver_init",
        "drivers/clk/meson/axg-aoclk.c:axg_aoclkc_driver_init",
        "drivers/clk/meson/gxbb.c:gxbb_driver_init",
        "drivers/clk/meson/gxbb-aoclk.c:gxbb_aoclkc_driver_init",
        "drivers/clk/meson/g12a.c:g12a_driver_init",
        "drivers/clk/meson/g12a-aoclk.c:g12a_aoclkc_driver_init",
        "drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_driver_init",
        "drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_driver_init",
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_driver_init",
        "drivers/clk/mvebu/ap806-system-controller.c:ap806_clock_driver_init",
        "drivers/clk/mvebu/ap806-system-controller.c:ap806_syscon_legacy_driver_init",
        "drivers/clk/mvebu/cp110-system-controller.c:cp110_clock_driver_init",
        "drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_legacy_driver_init",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_driver_init",
        "drivers/clk/socfpga/clk-s10.c:s10_clk_init",
        "drivers/clk/sunxi/clk-mod0.c:sun4i_a10_mod0_clk_driver_init",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_driver_init",
        "drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_clk_driver_init",
        "drivers/clk/sunxi/clk-sun6i-apb0.c:sun6i_a31_apb0_clk_driver_init",
        "drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_driver_init",
        "drivers/clk/sunxi/clk-sun6i-ar100.c:sun6i_a31_ar100_clk_driver_init",
        "drivers/clk/sunxi-ng/ccu-sun50i-a64.c:sun50i_a64_ccu_driver_init",
        "drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_driver_init",
        "drivers/clk/sunxi-ng/ccu-sun8i-a83t.c:sun8i_a83t_ccu_driver_init",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_driver_init",
        "drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_init",
        "drivers/clk/zynqmp/clkc.c:zynqmp_clock_driver_init",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_driver_init",
        "drivers/dma/mv_xor.c:mv_xor_driver_init",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_driver_init",
        "drivers/soc/actions/owl-sps.c:owl_sps_init",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_power_driver_init",
        "drivers/soc/bcm/raspberrypi-power.c:rpi_power_driver_init",
        "drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_driver_init",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_driver_init",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_driver_init",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_driver_init",
        "drivers/soc/fsl/guts.c:fsl_guts_init",
        "drivers/soc/imx/gpcv2.c:imx_gpc_driver_init",
        "drivers/soc/imx/gpcv2.c:imx_pgc_domain_driver_init",
        "drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_drv_init",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_driver_init",
        "drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_driver_init",
        "drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_driver_init",
        "drivers/soc/qcom/cmd-db.c:cmd_db_device_init",
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_driver_init",
        "drivers/soc/qcom/rpmhpd.c:rpmhpd_init",
        "drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_drv_register",
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_driver_init",
        "drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_platform_driver_init",
        "drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_power_domain_driver_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/reset/reset-berlin.c:berlin_reset_driver_init",
        "drivers/reset/reset-imx7.c:imx7_reset_driver_init",
        "drivers/reset/reset-meson.c:meson_reset_driver_init",
        "drivers/reset/reset-qcom-aoss.c:qcom_aoss_reset_driver_init",
        "drivers/reset/reset-simple.c:reset_simple_driver_init",
        "drivers/reset/reset-zynqmp.c:zynqmp_reset_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_platform_driver_init",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_platform_driver_init",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_driver_init",
        "drivers/tty/serial/amba-pl011.c:pl011_init",
        "drivers/tty/serial/imx.c:imx_uart_init",
        "drivers/tty/serial/meson_uart.c:meson_uart_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/msm_serial.c:msm_serial_init",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_init",
        "drivers/tty/serial/owl-uart.c:owl_uart_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/iommu/arm-smmu.c:arm_smmu_driver_init",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_driver_init",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_init",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_init",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_init",
        "drivers/misc/sram.c:sram_init",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_init",
        "drivers/mfd/bcm2835-pm.c:bcm2835_pm_driver_init",
        "drivers/mfd/sun6i-prcm.c:sun6i_prcm_driver_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init",
        "drivers/mfd/altera-sysmgr.c:altr_sysmgr_init",
        "drivers/ata/ahci_imx.c:imx_ahci_driver_init",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_init",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_driver_init",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdiomux_iproc_driver_init",
        "drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_enet_driver_init",
        "drivers/net/ethernet/freescale/fec_main.c:fec_driver_init",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_driver_init",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_load",
        "drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_load",
        "drivers/net/ethernet/freescale/fman/mac.c:mac_driver_init",
        "drivers/net/ethernet/smsc/smc91x.c:smc_driver_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_module_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-orion.c:ehci_orion_init",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_driver_init",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_driver_init",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_driver_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_init_driver",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_driver_init",
        "drivers/power/reset/as3722-poweroff.c:as3722_poweroff_driver_init",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_driver_init",
        "drivers/power/reset/gpio-restart.c:gpio_restart_driver_init",
        "drivers/power/reset/hisi-reboot.c:hisi_reboot_driver_init",
        "drivers/power/reset/msm-poweroff.c:msm_restart_init",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/reset/vexpress-poweroff.c:vexpress_reset_init",
        "drivers/power/reset/syscon-reboot.c:syscon_reboot_driver_init",
        "drivers/power/reset/syscon-poweroff.c:syscon_poweroff_register",
        "drivers/power/reset/sc27xx-poweroff.c:sc27xx_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/thermal/armada_thermal.c:armada_thermal_driver_init",
        "drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_driver_init",
        "drivers/edac/altera_edac.c:altr_edac_a10_driver_init",
        "drivers/edac/altera_edac.c:altr_edac_device_driver_init",
        "drivers/edac/altera_edac.c:altr_edac_driver_init",
        "drivers/edac/altera_edac.c:altr_sdram_edac_driver_init",
        "drivers/cpufreq/cpufreq-dt.c:dt_cpufreq_platdrv_init",
        "drivers/leds/leds-syscon.c:syscon_led_driver_init",
        "drivers/firmware/arm_sdei.c:sdei_init",
        "drivers/firmware/raspberrypi.c:rpi_firmware_driver_init",
        "drivers/firmware/qcom_scm.c:qcom_scm_init",
        "drivers/firmware/ti_sci.c:ti_sci_driver_init",
        "drivers/firmware/arm_scmi/driver.c:scmi_driver_init",
        "drivers/firmware/imx/imx-dsp.c:imx_dsp_driver_init",
        "drivers/firmware/imx/imx-scu.c:imx_scu_driver_init",
        "drivers/firmware/imx/scu-pd.c:imx_sc_pd_driver_init",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_driver_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_init",
        "drivers/clocksource/sh_tmu.c:sh_tmu_init",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_driver_init",
        "drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_driver_init",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_driver_init",
        "drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_init",
        "drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_driver_init",
        "drivers/memory/fsl_ifc.c:fsl_ifc_init",
        "drivers/memory/mtk-smi.c:mtk_smi_init",
        "drivers/memory/mtk-smi.c:mtk_smi_init",
        "drivers/perf/arm-cci.c:cci_pmu_driver_init",
        "drivers/perf/arm-ccn.c:arm_ccn_init",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_init",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_init",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_init",
        "drivers/perf/qcom_l2_pmu.c:register_l2_cache_pmu_driver",
        "drivers/perf/qcom_l3_pmu.c:register_qcom_l3_cache_pmu_driver",
        "drivers/perf/xgene_pmu.c:xgene_pmu_driver_init",
        "drivers/nvmem/zynqmp_nvmem.c:zynqmp_nvmem_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498992760,
      "name": "__platform_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231561908,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:732",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "arch/arm/kernel/perf_event_v7.c:armv7_pmu_driver_init",
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_init",
        "arch/arm/plat-omap/dma.c:omap_system_dma_init",
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "fs/pstore/ram.c:ramoops_init",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_init",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_init",
        "drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_init",
        "drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_driver_init",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_driver_init",
        "drivers/bus/arm-cci.c:cci_platform_init",
        "drivers/bus/imx-weim.c:weim_driver_init",
        "drivers/bus/omap_l3_smx.c:omap3_l3_init",
        "drivers/bus/omap_l3_noc.c:omap_l3_init",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_driver_init",
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_driver_init",
        "drivers/bus/ti-sysc.c:sysc_init",
        "drivers/bus/uniphier-system-bus.c:uniphier_system_bus_driver_init",
        "drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_driver_init",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_driver_init",
        "drivers/phy/samsung/phy-exynos-dp-video.c:exynos_dp_video_phy_driver_init",
        "drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_driver_init",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos_pcie_phy_driver_init",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_driver_init",
        "drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_driver_init",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_driver_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/meson/pinctrl-meson8.c:meson8_pinctrl_driver_init",
        "drivers/pinctrl/meson/pinctrl-meson8b.c:meson8b_pinctrl_driver_init",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_driver_init",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_drv_register",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_init",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_init",
        "drivers/pinctrl/pinctrl-rzn1.c:_pinctrl_drv_register",
        "drivers/pinctrl/pinctrl-single.c:pcs_driver_init",
        "drivers/pinctrl/tegra/pinctrl-tegra20.c:tegra20_pinctrl_init",
        "drivers/pinctrl/tegra/pinctrl-tegra30.c:tegra30_pinctrl_init",
        "drivers/pinctrl/tegra/pinctrl-tegra114.c:tegra114_pinctrl_init",
        "drivers/pinctrl/tegra/pinctrl-tegra124.c:tegra124_pinctrl_init",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_driver_init",
        "drivers/pinctrl/actions/pinctrl-s700.c:s700_pinctrl_init",
        "drivers/pinctrl/actions/pinctrl-s900.c:s900_pinctrl_init",
        "drivers/pinctrl/aspeed/pinctrl-aspeed-g6.c:aspeed_g6_pinctrl_init",
        "drivers/pinctrl/berlin/berlin-bg2.c:berlin2_pinctrl_driver_init",
        "drivers/pinctrl/berlin/berlin-bg2cd.c:berlin2cd_pinctrl_driver_init",
        "drivers/pinctrl/berlin/berlin-bg2q.c:berlin2q_pinctrl_driver_init",
        "drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_driver_init",
        "drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_driver_init",
        "drivers/pinctrl/freescale/pinctrl-imx50.c:imx50_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx51.c:imx51_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx6q.c:imx6q_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx6dl.c:imx6dl_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx6sl.c:imx6sl_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx6sll.c:imx6sll_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx6sx.c:imx6sx_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx6ul.c:imx6ul_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx7d.c:imx7d_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-imx7ulp.c:imx7ulp_pinctrl_init",
        "drivers/pinctrl/freescale/pinctrl-vf610.c:vf610_pinctrl_init",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_driver_init",
        "drivers/pinctrl/mvebu/pinctrl-armada-370.c:armada_370_pinctrl_driver_init",
        "drivers/pinctrl/mvebu/pinctrl-armada-375.c:armada_375_pinctrl_driver_init",
        "drivers/pinctrl/mvebu/pinctrl-armada-38x.c:armada_38x_pinctrl_driver_init",
        "drivers/pinctrl/mvebu/pinctrl-armada-39x.c:armada_39x_pinctrl_driver_init",
        "drivers/pinctrl/mvebu/pinctrl-armada-xp.c:armada_xp_pinctrl_driver_init",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_register",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_drv_register",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_init",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_driver_init",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-ld4.c:uniphier_ld4_pinctrl_driver_init",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-pro4.c:uniphier_pro4_pinctrl_driver_init",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-sld8.c:uniphier_sld8_pinctrl_driver_init",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-pro5.c:uniphier_pro5_pinctrl_driver_init",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-pxs2.c:uniphier_pxs2_pinctrl_driver_init",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-ld6b.c:uniphier_ld6b_pinctrl_driver_init",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-ld11.c:uniphier_ld11_pinctrl_driver_init",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-ld20.c:uniphier_ld20_pinctrl_driver_init",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-pxs3.c:uniphier_pxs3_pinctrl_driver_init",
        "drivers/pinctrl/mediatek/pinctrl-mt2701.c:mtk_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt8135.c:mtk_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt8127.c:mtk_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt7623.c:mtk_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt7629.c:mt7629_pinctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-mt6397.c:mtk_pinctrl_driver_init",
        "drivers/gpio/gpio-mmio.c:bgpio_driver_init",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_driver_init",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_init",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_driver_init",
        "drivers/gpio/gpio-mxc.c:gpio_mxc_init",
        "drivers/gpio/gpio-omap.c:omap_gpio_drv_reg",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_init",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_init",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-twl4030.c:gpio_twl4030_init",
        "drivers/gpio/gpio-twl6040.c:gpo_twl6040_driver_init",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_driver_init",
        "drivers/gpio/gpio-xilinx.c:xgpio_init",
        "drivers/gpio/gpio-zevio.c:zevio_gpio_driver_init",
        "drivers/pwm/pwm-tipwmss.c:pwmss_driver_init",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_driver_init",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_driver_init",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_driver_init",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_driver_init",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_driver_init",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_driver_init",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_driver_init",
        "drivers/pci/controller/pci-host-generic.c:gen_pci_driver_init",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_driver_init",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_driver_init",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_driver_init",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_init",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_driver_init",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_driver_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_driver_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_driver_init",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_platform_driver_init",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/mx3fb.c:mx3fb_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/amba/tegra-ahb.c:tegra_ahb_driver_init",
        "drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_driver_init",
        "drivers/clk/clk-fixed-rate.c:of_fixed_clk_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_driver_init",
        "drivers/clk/clk-aspeed.c:aspeed_clk_driver_init",
        "drivers/clk/clk-ast2600.c:aspeed_g6_clk_driver_init",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_driver_init",
        "drivers/clk/clk-milbeaut.c:m10v_clk_driver_init",
        "drivers/clk/actions/owl-s500.c:s500_clk_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_init",
        "drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_init",
        "drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_init",
        "drivers/clk/mediatek/clk-mt7622.c:clk_mt7622_init",
        "drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_eth_drv_init",
        "drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_hif_drv_init",
        "drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_aud_drv_init",
        "drivers/clk/mediatek/clk-mt7629.c:clk_mt7629_init",
        "drivers/clk/mediatek/clk-mt7629-eth.c:clk_mt7629_eth_drv_init",
        "drivers/clk/mediatek/clk-mt7629-hif.c:clk_mt7629_hif_drv_init",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_driver_init",
        "drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_drv_init",
        "drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_drv_init",
        "drivers/clk/tegra/clk-tegra124-dfll-fcpu.c:tegra124_dfll_fcpu_driver_init",
        "drivers/clk/ti/clk-dra7-atl.c:dra7_atl_clk_driver_init",
        "drivers/clk/ti/adpll.c:ti_adpll_init",
        "drivers/clk/uniphier/clk-uniphier-core.c:uniphier_clk_driver_init",
        "drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_init",
        "drivers/dma/mv_xor.c:mv_xor_driver_init",
        "drivers/dma/tegra20-apb-dma.c:tegra_dmac_driver_init",
        "drivers/dma/ti/omap-dma.c:omap_dma_init",
        "drivers/dma/ti/dma-crossbar.c:omap_dmaxbar_init",
        "drivers/soc/actions/owl-sps.c:owl_sps_init",
        "drivers/soc/fsl/guts.c:fsl_guts_init",
        "drivers/soc/imx/gpc.c:imx_gpc_driver_init",
        "drivers/soc/imx/gpc.c:imx_pgc_power_domain_driver_init",
        "drivers/soc/imx/gpcv2.c:imx_gpc_driver_init",
        "drivers/soc/imx/gpcv2.c:imx_pgc_domain_driver_init",
        "drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_drv_init",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_msr_driver_init",
        "drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_driver_init",
        "drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_driver_init",
        "drivers/soc/qcom/cmd-db.c:cmd_db_device_init",
        "drivers/soc/qcom/spm.c:spm_driver_init",
        "drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_drv_register",
        "drivers/soc/samsung/exynos-pmu.c:exynos_pmu_init",
        "drivers/soc/tegra/fuse/fuse-tegra.c:tegra_fuse_driver_init",
        "drivers/soc/tegra/flowctrl.c:tegra_flowctrl_driver_init",
        "drivers/soc/tegra/pmc.c:tegra_pmc_driver_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/regulator/fixed.c:regulator_fixed_voltage_init",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_driver_init",
        "drivers/regulator/tps65217-regulator.c:tps65217_regulator_init",
        "drivers/regulator/twl-regulator.c:twlreg_init",
        "drivers/regulator/twl6030-regulator.c:twlreg_init",
        "drivers/reset/reset-berlin.c:berlin_reset_driver_init",
        "drivers/reset/reset-imx7.c:imx7_reset_driver_init",
        "drivers/reset/reset-meson.c:meson_reset_driver_init",
        "drivers/reset/reset-qcom-aoss.c:qcom_aoss_reset_driver_init",
        "drivers/reset/reset-simple.c:reset_simple_driver_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_platform_driver_init",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_driver_init",
        "drivers/tty/serial/amba-pl011.c:pl011_init",
        "drivers/tty/serial/imx.c:imx_uart_init",
        "drivers/tty/serial/meson_uart.c:meson_uart_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/msm_serial.c:msm_serial_init",
        "drivers/tty/serial/omap-serial.c:serial_omap_init",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_init",
        "drivers/tty/serial/owl-uart.c:owl_uart_init",
        "drivers/tty/serial/rda-uart.c:rda_uart_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_init",
        "drivers/iommu/omap-iommu.c:omap_iommu_init",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_init",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_init",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_init",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_init",
        "drivers/misc/sram.c:sram_init",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_init",
        "drivers/mfd/sm501.c:sm501_base_init",
        "drivers/mfd/t7l66xb.c:t7l66xb_platform_driver_init",
        "drivers/mfd/tc6387xb.c:tc6387xb_platform_driver_init",
        "drivers/mfd/tc6393xb.c:tc6393xb_init",
        "drivers/mfd/twl4030-power.c:twl4030_power_driver_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/omap-usb-host.c:omap_usbhs_drvinit",
        "drivers/mfd/omap-usb-tll.c:omap_usbtll_drvinit",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init",
        "drivers/ata/ahci_platform.c:ahci_driver_init",
        "drivers/ata/sata_highbank.c:ahci_highbank_driver_init",
        "drivers/ata/ahci_imx.c:imx_ahci_driver_init",
        "drivers/mtd/nand/raw/omap2.c:omap_nand_driver_init",
        "drivers/mtd/nand/raw/omap_elm.c:elm_driver_init",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_init",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_driver_init",
        "drivers/net/ethernet/freescale/fec_main.c:fec_driver_init",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_driver_init",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_init",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_driver_init",
        "drivers/usb/phy/phy-generic.c:usb_phy_generic_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_module_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-orion.c:ehci_orion_init",
        "drivers/usb/host/ehci-exynos.c:ehci_exynos_init",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/ohci-exynos.c:ohci_exynos_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/musb/musb_core.c:musb_driver_init",
        "drivers/rtc/rtc-omap.c:omap_rtc_driver_init",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_driver_init",
        "drivers/rtc/rtc-twl.c:twl4030rtc_driver_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/i2c/busses/i2c-imx.c:i2c_adap_imx_init",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_init_driver",
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_adap_s3c_init",
        "drivers/power/avs/smartreflex.c:sr_init",
        "drivers/power/reset/as3722-poweroff.c:as3722_poweroff_driver_init",
        "drivers/power/reset/brcm-kona-reset.c:bcm_kona_reset_driver_init",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_driver_init",
        "drivers/power/reset/gpio-restart.c:gpio_restart_driver_init",
        "drivers/power/reset/hisi-reboot.c:hisi_reboot_driver_init",
        "drivers/power/reset/msm-poweroff.c:msm_restart_init",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/reset/vexpress-poweroff.c:vexpress_reset_init",
        "drivers/power/reset/syscon-reboot.c:syscon_reboot_driver_init",
        "drivers/power/reset/syscon-poweroff.c:syscon_poweroff_register",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_driver_init",
        "drivers/thermal/armada_thermal.c:armada_thermal_driver_init",
        "drivers/watchdog/npcm_wdt.c:npcm_wdt_driver_init",
        "drivers/watchdog/aspeed_wdt.c:aspeed_wdt_init",
        "drivers/opp/ti-opp-supply.c:ti_opp_supply_driver_init",
        "drivers/cpufreq/cpufreq-dt.c:dt_cpufreq_platdrv_init",
        "drivers/cpufreq/omap-cpufreq.c:omap_cpufreq_platdrv_init",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_driver_init",
        "drivers/cpufreq/tegra124-cpufreq.c:tegra_cpufreq_init",
        "drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_driver_init",
        "drivers/cpuidle/cpuidle-mvebu-v7.c:mvebu_cpuidle_driver_init",
        "drivers/cpuidle/cpuidle-exynos.c:exynos_cpuidle_driver_init",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_driver_init",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_driver_init",
        "drivers/leds/leds-asic3.c:asic3_led_driver_init",
        "drivers/leds/leds-syscon.c:syscon_led_driver_init",
        "drivers/firmware/qcom_scm.c:qcom_scm_init",
        "drivers/firmware/arm_scmi/driver.c:scmi_driver_init",
        "drivers/firmware/imx/imx-dsp.c:imx_dsp_driver_init",
        "drivers/firmware/imx/imx-scu.c:imx_scu_driver_init",
        "drivers/firmware/imx/scu-pd.c:imx_sc_pd_driver_init",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_init",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_init",
        "drivers/clocksource/sh_tmu.c:sh_tmu_init",
        "drivers/clocksource/em_sti.c:em_sti_init",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_driver_init",
        "drivers/staging/emxx_udc/emxx_udc.c:udc_driver_init",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_driver_init",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_init",
        "drivers/devfreq/exynos-bus.c:exynos_bus_platdrv_init",
        "drivers/devfreq/event/exynos-nocp.c:exynos_nocp_driver_init",
        "drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_driver_init",
        "drivers/memory/omap-gpmc.c:gpmc_init",
        "drivers/memory/mvebu-devbus.c:mvebu_devbus_init",
        "drivers/memory/mtk-smi.c:mtk_smi_init",
        "drivers/memory/mtk-smi.c:mtk_smi_init",
        "drivers/memory/samsung/exynos-srom.c:exynos_srom_driver_init",
        "drivers/memory/tegra/mc.c:tegra_mc_init",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_init",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_init",
        "drivers/perf/arm-cci.c:cci_pmu_driver_init",
        "drivers/perf/arm-ccn.c:arm_ccn_init",
        "sound/soc/soc-core.c:snd_soc_init",
        "sound/soc/soc-utils.c:snd_soc_util_init",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_driver_init",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_init",
        "sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231561028,
      "name": "__platform_driver_register",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292149128,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:732",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_init",
        "arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_driver_init",
        "arch/powerpc/platforms/powernv/vas.c:vas_init",
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_driver_init",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_driver_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_driver_init",
        "drivers/pinctrl/pinctrl-single.c:pcs_driver_init",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_driver_init",
        "drivers/gpio/gpio-mmio.c:bgpio_driver_init",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_driver_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_init",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-xilinx.c:xgpio_init",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_driver_init",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_driver_init",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_driver_init",
        "drivers/pci/controller/pci-host-generic.c:gen_pci_driver_init",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/soc/fsl/guts.c:fsl_guts_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/hvc/hvc_opal.c:hvc_opal_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_driver_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/rtc/rtc-opal.c:opal_rtc_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/i2c/busses/i2c-opal.c:i2c_opal_init",
        "drivers/power/reset/as3722-poweroff.c:as3722_poweroff_driver_init",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_driver_init",
        "drivers/power/reset/gpio-restart.c:gpio_restart_driver_init",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/reset/syscon-reboot.c:syscon_reboot_driver_init",
        "drivers/power/reset/syscon-poweroff.c:syscon_poweroff_register",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/leds/leds-syscon.c:syscon_led_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292147744,
      "name": "__platform_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276368262,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:732",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_driver_init",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_driver_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_driver_init",
        "drivers/pinctrl/pinctrl-single.c:pcs_driver_init",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_driver_init",
        "drivers/gpio/gpio-mmio.c:bgpio_driver_init",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_driver_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_init",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_driver_init",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_driver_init",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_driver_init",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_driver_init",
        "drivers/pci/controller/pci-host-generic.c:gen_pci_driver_init",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_driver_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_driver_init",
        "drivers/clk/clk-fixed-rate.c:of_fixed_clk_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_driver_init",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_driver_init",
        "drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_driver_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/tty/serial/sifive.c:sifive_serial_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_init",
        "drivers/spi/spi-sifive.c:sifive_spi_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/as3722-poweroff.c:as3722_poweroff_driver_init",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_driver_init",
        "drivers/power/reset/gpio-restart.c:gpio_restart_driver_init",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/reset/syscon-reboot.c:syscon_reboot_driver_init",
        "drivers/power/reset/syscon-poweroff.c:syscon_poweroff_register",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/leds/leds-syscon.c:syscon_led_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276367356,
      "name": "__platform_driver_register",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585954353,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:732",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/gpio/gpio-mmio.c:bgpio_driver_init",
        "drivers/gpio/gpio-xilinx.c:xgpio_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585953904,
      "name": "__platform_driver_register",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585803569,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:732",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-xilinx.c:xgpio_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-st.c:st_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585803120,
      "name": "__platform_driver_register",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586144161,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:732",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-st.c:st_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_plat_driver_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586143712,
      "name": "__platform_driver_register",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __platform_driver_register(struct platform_driver * drv, struct module * owner)
```

```json
{
  "name": "__platform_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586252849,
      "name": "__platform_driver_register",
      "external": true,
      "loc": "drivers/base/platform.c:732",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_register_drivers"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_init",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_init",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_init",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_init",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_init",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_init",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_init",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_driver_init",
        "drivers/gpio/gpio-xilinx.c:xgpio_init",
        "drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_init",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_init",
        "drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_driver_init",
        "drivers/video/fbdev/vesafb.c:vesafb_driver_init",
        "drivers/video/fbdev/efifb.c:efifb_driver_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/acpi/fan.c:acpi_fan_driver_init",
        "drivers/acpi/apei/ghes.c:ghes_init",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_driver_init",
        "drivers/clk/clk-gpio.c:gpio_clk_driver_init",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_driver_init",
        "drivers/clk/x86/clk-st.c:st_clk_driver_init",
        "drivers/clk/x86/clk-lpt.c:lpt_clk_init",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_init",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_init",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/misc/sram.c:sram_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_driver_init",
        "drivers/mfd/syscon.c:syscon_init",
        "drivers/nvdimm/e820.c:e820_pmem_driver_init",
        "drivers/usb/dwc2/platform.c:dwc2_platform_driver_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_init",
        "drivers/usb/host/ohci-platform.c:ohci_platform_init",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_init_driver",
        "drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586252400,
      "name": "__platform_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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

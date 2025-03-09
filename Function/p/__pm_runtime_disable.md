# Function: <code>__pm_runtime_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584447488,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1168",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447488,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584783552,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1172",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783552,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972944,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1260",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972944,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585058768,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1260",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058768,
      "name": "__pm_runtime_disable",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585481600,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1245",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481600,
      "name": "__pm_runtime_disable",
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585724880,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1245",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585724880,
      "name": "__pm_runtime_disable",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585856864,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1252",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856864,
      "name": "__pm_runtime_disable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586094144,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1328",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094144,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586241696,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1330",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586241696,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587008352,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1351",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008352,
      "name": "__pm_runtime_disable",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587093808,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1383",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587093808,
      "name": "__pm_runtime_disable",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586980016,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1383",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586980016,
      "name": "__pm_runtime_disable",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587543568,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1402",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587543568,
      "name": "__pm_runtime_disable",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588877424,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1431",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877424,
      "name": "__pm_runtime_disable",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590385696,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1444",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume_common",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590385696,
      "name": "__pm_runtime_disable",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590705488,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1444",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serial/serial_ctrl.c:serial_ctrl_remove",
        "drivers/tty/serial/serial_port.c:serial_port_remove",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume_common",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590705488,
      "name": "__pm_runtime_disable",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591067344,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1445",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serial/serial_ctrl.c:serial_ctrl_remove",
        "drivers/tty/serial/serial_port.c:serial_port_remove",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume_common",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591067344,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499057712,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1330",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_remove",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_remove",
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_remove",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_remove",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe",
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_remove",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libahci_platform.c:ahci_platform_put_resources",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_remove",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/memory/mtk-smi.c:mtk_smi_common_remove",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499057712,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231614996,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1330",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_remove",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_remove",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_remove",
        "drivers/bus/ti-sysc.c:sysc_remove",
        "drivers/bus/ti-sysc.c:sysc_remove",
        "drivers/bus/ti-sysc.c:sysc_probe",
        "drivers/bus/ti-sysc.c:sysc_probe",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-omap.c:omap_gpio_remove",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/pwm/pwm-tipwmss.c:pwmss_remove",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_remove",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_subsys_powerdown",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_shutdown",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe",
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_remove",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup",
        "drivers/tty/serial/omap-serial.c:serial_omap_remove",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/omap-iommu.c:omap_iommu_remove",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_remove",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe",
        "drivers/mfd/omap-usb-tll.c:usbtll_omap_remove",
        "drivers/mfd/omap-usb-tll.c:usbtll_omap_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libahci_platform.c:ahci_platform_put_resources",
        "drivers/mtd/nand/raw/omap_elm.c:elm_remove",
        "drivers/mtd/nand/raw/omap_elm.c:elm_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_remove",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_remove",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/musb/musb_core.c:musb_remove",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/rtc/rtc-omap.c:omap_rtc_remove",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_remove",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_remove",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_remove",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_remove",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe",
        "drivers/memory/omap-gpmc.c:gpmc_remove",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_remove",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231614996,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292230976,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1330",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_remove",
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_remove",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292230976,
      "name": "__pm_runtime_disable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276414892,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1330",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_remove",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/block.c:mmc_blk_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276414892,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586001904,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1330",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586001904,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585851072,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1330",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585851072,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586191712,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1330",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586191712,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void __pm_runtime_disable(struct device * dev, bool check_resume)
```

```json
{
  "name": "__pm_runtime_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586301376,
      "name": "__pm_runtime_disable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1330",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586301376,
      "name": "__pm_runtime_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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

# Function: <code>pm_runtime_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584440096,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1207",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440096,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776032,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1211",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776032,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584966448,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1299",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584966448,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585050928,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1299",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050928,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585473760,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1284",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585473760,
      "name": "pm_runtime_enable",
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717696,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1284",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717696,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585849440,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1291",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585849440,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1370",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586096715,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586086720,
      "name": "pm_runtime_enable",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1372",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586244267,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586234272,
      "name": "pm_runtime_enable",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1393",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587012747,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587000944,
      "name": "pm_runtime_enable",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1425",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591488568,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587085552,
      "name": "pm_runtime_enable",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1425",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591431614,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586971824,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1444",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592491080,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587537952,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1475",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594360824,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588869664,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590377280,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1488",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume_common",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590377280,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590697712,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1488",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serial/serial_ctrl.c:serial_ctrl_probe",
        "drivers/tty/serial/serial_port.c:serial_port_probe",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume_common",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590697712,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591059568,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1489",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serial/serial_ctrl.c:serial_ctrl_probe",
        "drivers/tty/serial/serial_port.c:serial_port_probe",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume_common",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591059568,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499048944,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1372",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_probe",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe",
        "drivers/amba/bus.c:amba_probe",
        "drivers/clk/mediatek/clk-mt8183-mfgcfg.c:clk_mt8183_mfg_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_probe",
        "drivers/clocksource/sh_tmu.c:sh_tmu_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499048944,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231605640,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1372",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_probe",
        "drivers/bus/ti-sysc.c:sysc_probe",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/pwm/pwm-tipwmss.c:pwmss_probe",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe",
        "drivers/amba/bus.c:amba_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_probe",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/dma/ti/edma.c:edma_tptc_probe",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/omap-iommu.c:omap_iommu_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe",
        "drivers/mfd/omap-usb-tll.c:usbtll_omap_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/mtd/nand/raw/omap_elm.c:elm_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe",
        "drivers/power/avs/smartreflex.c:omap_sr_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_probe",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_probe",
        "drivers/clocksource/sh_tmu.c:sh_tmu_probe",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231605640,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292221472,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1372",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_probe",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292221472,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276406940,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1372",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/simple-pm-bus.c:simple_pm_bus_probe",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276406940,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1372",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586004475,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585994480,
      "name": "pm_runtime_enable",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1372",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853589,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585843728,
      "name": "pm_runtime_enable",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1372",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194283,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586184288,
      "name": "pm_runtime_enable",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void pm_runtime_enable(struct device * dev)
```

```json
{
  "name": "pm_runtime_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_runtime_enable",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1372",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586302850,
      "name": "pm_runtime_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586293488,
      "name": "pm_runtime_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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

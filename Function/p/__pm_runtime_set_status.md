# Function: <code>__pm_runtime_set_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584445680,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1009",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/mmc/core/mmc.c:mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445680,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584781632,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1009",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584781632,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584973328,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1087",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973328,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585056880,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1087",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585056880,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585479792,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1088",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_noirq",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585479792,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585721072,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1088",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585721072,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585852960,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1095",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585852960,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1131",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586096742,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071586092960,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1133",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586244294,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071586240512,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1154",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587012774,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071587009392,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1186",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591488595,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071587094128,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1186",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591431641,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071586980336,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 951
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1205",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592491107,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587544768,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 953
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1233",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594360871,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071588878624,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590387008,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1246",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume_common",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590387008,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590706752,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1246",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume_common",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590706752,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 854
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591068608,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1247",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ehci-platform.c:ehci_platform_resume",
        "drivers/usb/host/ohci-platform.c:ohci_platform_resume_common",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068608,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 854
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499055888,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1133",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_probe",
        "drivers/amba/bus.c:amba_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_probe",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_probe",
        "drivers/clocksource/sh_tmu.c:sh_tmu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499055888,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 924
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231614136,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1133",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/omap_device.c:_omap_device_notifier_call",
        "arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_probe",
        "drivers/amba/bus.c:amba_probe",
        "drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_probe",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_probe",
        "drivers/clocksource/sh_tmu.c:sh_tmu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231614136,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292228880,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1133",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292228880,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276413528,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1133",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276413528,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1133",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586004502,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071586000720,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1133",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853616,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071585849920,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1133",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194310,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071586190528,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
int __pm_runtime_set_status(struct device * dev, unsigned int status)
```

```json
{
  "name": "__pm_runtime_set_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_runtime_set_status",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1133",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/ata/libata-core.c:ata_port_pm_resume",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_resume",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586302877,
      "name": "__pm_runtime_set_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071586300624,
      "name": "__pm_runtime_set_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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

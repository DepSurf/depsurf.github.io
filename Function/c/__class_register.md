# Function: <code>__class_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404144,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:166",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "net/core/net-sysfs.c:netdev_kobject_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404144,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584739488,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:166",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "net/core/net-sysfs.c:netdev_kobject_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739488,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584929376,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:178",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "net/core/net-sysfs.c:netdev_kobject_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584929376,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585014128,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:148",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "net/core/net-sysfs.c:netdev_kobject_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585014128,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585436384,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:148",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "net/core/net-sysfs.c:netdev_kobject_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436384,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585679504,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:146",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679504,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585809728,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:146",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585809728,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042976,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:152",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042976,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586190608,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:152",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190608,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951360,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:153",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951360,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036336,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:153",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036336,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586920128,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:153",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920128,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587482528,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:153",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587482528,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588804352,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:153",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/sysfs.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588804352,
      "name": "__class_register",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590301680,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:153",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/sysfs.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590301680,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498988144,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:152",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498988144,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231556460,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:152",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/mtd/mtdcore.c:init_mtd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231556460,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292143952,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:152",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292143952,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276365200,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:152",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276365200,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585950976,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:152",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950976,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585800032,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:152",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585800032,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586140624,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:152",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586140624,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __class_register(struct class * cls, struct lock_class_key * key)
```

```json
{
  "name": "__class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586249312,
      "name": "__class_register",
      "external": true,
      "loc": "drivers/base/class.c:152",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/class.c:__class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/fallback.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586249312,
      "name": "__class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int __class_register(struct class * cls, struct lock_class_key * key)
```
</details>
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

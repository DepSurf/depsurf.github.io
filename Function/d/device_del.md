# Function: <code>device_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584378320,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:1232",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "block/genhd.c:add_disk",
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition",
        "block/partition-generic.c:add_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/base/core.c:device_unregister",
        "drivers/base/platform.c:platform_device_del",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:rtc_device_unregister",
        "drivers/power/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378320,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584713296,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:1232",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/base/core.c:device_unregister",
        "drivers/base/platform.c:platform_device_del",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:rtc_device_unregister",
        "drivers/power/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713296,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584904240,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:1818",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/base/core.c:device_unregister",
        "drivers/base/platform.c:platform_device_del",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:rtc_device_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584904240,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584989456,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:1816",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/nvmem/core.c:nvmem_unregister",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584989456,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 838
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585411392,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:1951",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/nvmem/core.c:nvmem_unregister",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585411392,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585653328,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:1998",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/nvmem/core.c:nvmem_unregister",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585653328,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585782880,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2077",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/nvmem/core.c:nvmem_device_release",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585782880,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2299",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/nvmem/core.c:nvmem_device_release",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586023902,
      "name": "device_del.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586013216,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 874
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586160736,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2336",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/nvmem/core.c:nvmem_device_release",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160736,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586918848,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2834",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:register_disk",
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:delete_partition",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918848,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 711
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587003008,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:3243",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:register_disk",
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:delete_partition",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dax_mapping",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003008,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586885520,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:3470",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:register_disk",
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:delete_partition",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dax_mapping",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885520,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587447520,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:3535",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:delete_partition",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dax_mapping",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447520,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1007
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588765104,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:3570",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:delete_partition",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del_work_fn",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dax_mapping",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588765104,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590256224,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:3769",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:delete_partition",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del_work_fn",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dax_mapping",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590256224,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590575504,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:3768",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:bdev_disk_changed",
        "block/partitions/core.c:bdev_del_partition",
        "block/partitions/core.c:add_partition",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del_work_fn",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serial/serial_base_bus.c:serial_base_port_device_remove",
        "drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_device_remove",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590575504,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 979
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590933904,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:3782",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:bdev_disk_changed",
        "block/partitions/core.c:bdev_del_partition",
        "block/partitions/core.c:add_partition",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del_work_fn",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serial/serial_base_bus.c:serial_base_port_device_remove",
        "drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_device_remove",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/gpu/drm/drm_drv.c:drm_minor_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590933904,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 979
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498956392,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2336",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_remove",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/nvmem/core.c:nvmem_device_release",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498956392,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231527548,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2336",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release",
        "drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/nvmem/core.c:nvmem_device_release",
        "sound/core/sound.c:snd_unregister_device",
        "sound/core/init.c:snd_card_disconnect",
        "sound/soc/soc-ac97.c:snd_soc_free_ac97_component",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231527548,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292099712,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2336",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper",
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_transport_srp.c:srp_rport_del",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/nvmem/core.c:nvmem_device_release",
        "drivers/nvmem/core.c:nvmem_device_release",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292099712,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1124
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276338432,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2336",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/nvmem/core.c:nvmem_device_release",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276338432,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585921104,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2336",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/nvme/host/core.c:nvme_destroy_subsystem",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/nvmem/core.c:nvmem_device_release",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585921104,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585770240,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2336",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_transport_fc.c:fc_vport_terminate",
        "drivers/scsi/scsi_transport_fc.c:fc_vport_setup",
        "drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/nvme/host/core.c:nvme_destroy_subsystem",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/nvmem/core.c:nvmem_device_release",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585770240,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586110752,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2336",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/nvmem/core.c:nvmem_device_release",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586110752,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
void device_del(struct device * dev)
```

```json
{
  "name": "device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586219360,
      "name": "device_del",
      "external": true,
      "loc": "drivers/base/core.c:2336",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_del",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:delete_partition",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_unregister",
        "drivers/base/attribute_container.c:attribute_container_class_device_del",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:devcd_del",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/ata/libata-transport.c:ata_tdev_delete",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_delete",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/ata/libata-transport.c:ata_tport_delete",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/phy_device.c:phy_device_remove",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_remove",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/mmc/core/bus.c:mmc_remove_card",
        "drivers/mmc/core/host.c:mmc_remove_host",
        "drivers/mmc/core/sdio_bus.c:sdio_remove_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "drivers/nvmem/core.c:nvmem_device_release",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586219360,
      "name": "device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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

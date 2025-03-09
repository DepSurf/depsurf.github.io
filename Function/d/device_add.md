# Function: <code>device_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584383984,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:1025",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_create",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/power/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383984,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1657
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584718912,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:1025",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_create",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_device.c:mdio_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/power/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584718912,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1618
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584908752,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:1607",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_create",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_device.c:mdio_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584908752,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1579
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584993952,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:1605",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584993952,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1656
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585415840,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:1740",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585415840,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1662
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585658608,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:1782",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585658608,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1604
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585784800,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:1858",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585784800,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1682
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586015632,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2062",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586015632,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1698
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586163344,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2099",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586163344,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1698
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586921680,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2579",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:register_disk",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:__cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device_adapter",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tdev_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/host.c:mmc_add_host",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586921680,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1691
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587013536,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2988",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:register_disk",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:__cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device_adapter",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:__auxiliary_device_add",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tdev_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/host.c:mmc_add_host",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587013536,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1516
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586897024,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:3206",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:register_disk",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device_adapter",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:__auxiliary_device_add",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/host.c:mmc_add_host",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586897024,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1661
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:3274",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device_adapter",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:__auxiliary_device_add",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:__spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_device.c:mdio_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592488026,
      "name": "device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587458416,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1954
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:3309",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device_adapter",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:__auxiliary_device_add",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:__spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/net/phy/mdio_device.c:mdio_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594357664,
      "name": "device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588777392,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2054
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:3507",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device_adapter",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:__auxiliary_device_add",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:__spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596245832,
      "name": "device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590271312,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1825
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:3508",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serial/serial_base_bus.c:serial_base_port_add",
        "drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device_adapter",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:__auxiliary_device_add",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_register",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:__spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596774260,
      "name": "device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590591776,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1792
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:3521",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serial/serial_base_bus.c:serial_base_port_add",
        "drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device_adapter",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:__auxiliary_device_add",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback",
        "drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_register",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_drv.c:drm_minor_register",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:__spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_add",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597683511,
      "name": "device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590950576,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1856
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498958552,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2099",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_device_add",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498958552,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1600
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231529084,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2099",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release",
        "drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "sound/core/sound.c:snd_register_device",
        "sound/soc/soc-ac97.c:snd_soc_new_ac97_component",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231529084,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1620
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292102976,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2099",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_transport_srp.c:srp_rport_add",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/of/device.c:of_device_add",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292102976,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2100
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276340414,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2099",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276340414,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1394
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585923712,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2099",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/nvme/host/core.c:nvme_init_subsystem",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585923712,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1698
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585772848,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2099",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_transport_fc.c:fc_vport_setup",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_create",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/nvme/host/core.c:nvme_init_subsystem",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772848,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1698
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586113360,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2099",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586113360,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1698
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
int device_add(struct device * dev)
```

```json
{
  "name": "device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586221168,
      "name": "device_add",
      "external": true,
      "loc": "drivers/base/core.c:2099",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "fs/char_dev.c:cdev_device_add",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_device_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_class_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_async_device_register",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/net/phy/phy_device.c:phy_device_register",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/input.c:input_register_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_add_card",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221168,
      "name": "device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1698
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

# Function: <code>device_initialize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584376560,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:700",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_create",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/spi/spi.c:spi_alloc_master",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/power/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584376560,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584711536,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:700",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_create",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_alloc_master",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/power/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584711536,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584898752,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1266",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_create",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:spi_alloc_master",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898752,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584984368,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1264",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584984368,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585406192,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1399",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/hmm.c:hmm_device_new",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585406192,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585648512,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1441",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/hmm.c:hmm_device_new",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585648512,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585777936,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1515",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/hmm.c:hmm_device_new",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777936,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586010816,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1660",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586010816,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586157744,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1697",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586157744,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586915200,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:2175",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/cpu.c:__cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tdev_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586915200,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586999776,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:2585",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/cpu.c:__cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tdev_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586999776,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586882208,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:2797",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_alloc_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586882208,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587443840,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:2862",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_alloc_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc.c:edac_mc_alloc",
        "drivers/edac/edac_mc.c:edac_mc_alloc",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587443840,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588760512,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:2887",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_alloc_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:auxiliary_device_init",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/sysfs.c:fw_create_instance",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc.c:edac_mc_alloc",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588760512,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590249200,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:3085",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_alloc_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:auxiliary_device_init",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/sysfs.c:fw_create_instance",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc.c:edac_mc_alloc",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590249200,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590569232,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:3091",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_alloc_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serial/serial_base_bus.c:serial_base_device_init",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:auxiliary_device_init",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/sysfs.c:fw_create_instance",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc.c:edac_mc_alloc",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590569232,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590927632,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:3106",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_alloc_host_bridge",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/pmdomain/core.c:pm_genpd_init",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/serial/serial_base_bus.c:serial_base_device_init",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/auxiliary.c:auxiliary_device_init",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/firmware_loader/sysfs.c:fw_create_instance",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_minor_alloc",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc.c:edac_mc_alloc",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590927632,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498952008,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1697",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_device_add",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/amba/bus.c:amba_device_initialize",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/of/device.c:of_device_register",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498952008,
      "name": "device_initialize",
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231523180,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1697",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/amba/bus.c:amba_device_initialize",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release",
        "drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/of/device.c:of_device_register",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "sound/core/init.c:snd_card_new",
        "sound/core/init.c:snd_device_initialize",
        "sound/soc/soc-ac97.c:snd_soc_alloc_ac97_component",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231523180,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292094512,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1697",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_transport_srp.c:srp_rport_add",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/of/device.c:of_device_register",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292094512,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276335248,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1697",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/of/device.c:of_device_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276335248,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585918112,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1697",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/nvme/host/core.c:nvme_init_subsystem",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585918112,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585767248,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1697",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_transport_fc.c:fc_vport_setup",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_create",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/nvme/host/core.c:nvme_init_subsystem",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767248,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586107760,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1697",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107760,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void device_initialize(struct device * dev)
```

```json
{
  "name": "device_initialize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586216368,
      "name": "device_initialize",
      "external": true,
      "loc": "drivers/base/core.c:1697",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:pmu_dev_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add",
        "drivers/base/core.c:device_create_groups_vargs",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_alloc",
        "drivers/base/cpu.c:cpu_device_create",
        "drivers/base/attribute_container.c:attribute_container_add_device",
        "drivers/base/power/wakeup_stats.c:wakeup_source_device_create",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tlink_add",
        "drivers/ata/libata-transport.c:ata_tport_add",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/spi/spi.c:__spi_alloc_controller",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/phy/phy_device.c:phy_device_create",
        "drivers/net/phy/mdio_device.c:mdio_device_create",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_alloc_card",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/sdio_bus.c:sdio_alloc_func",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/rfkill/core.c:rfkill_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216368,
      "name": "device_initialize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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

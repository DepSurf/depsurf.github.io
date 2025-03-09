# Function: <code>driver_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584401824,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:188",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_driver_exit",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/mfd/wm831x-spi.c:wm831x_spi_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584401824,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584737168,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:188",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/wm831x-spi.c:wm831x_spi_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737168,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584927040,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:188",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/wm831x-spi.c:wm831x_spi_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584927040,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585011856,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:188",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/wm831x-spi.c:wm831x_spi_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011856,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585434096,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:188",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/wm831x-spi.c:wm831x_spi_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434096,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585677168,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/wm831x-spi.c:wm831x_spi_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677168,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585807424,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/wm831x-spi.c:wm831x_spi_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807424,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586040640,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/soundwire/bus_type.c:sdw_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586040640,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586188272,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586188272,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586949712,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:191",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949712,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587034784,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:191",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:auxiliary_driver_unregister",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034784,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586918576,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:191",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:auxiliary_driver_unregister",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918576,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587480992,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:191",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:auxiliary_driver_unregister",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587480992,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588802496,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:261",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:auxiliary_driver_unregister",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588802496,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590299360,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:267",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/tty/serial/max310x.c:max310x_uart_init",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:auxiliary_driver_unregister",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/staging/vme_user/vme.c:vme_unregister_driver",
        "drivers/staging/vme_user/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299360,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590619568,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:267",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/serial_base_bus.c:serial_base_driver_unregister",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/tty/serial/max310x.c:max310x_uart_init",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:auxiliary_driver_unregister",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/staging/vme_user/vme.c:vme_unregister_driver",
        "drivers/staging/vme_user/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590619568,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590978672,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:267",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/serial_base_bus.c:serial_base_driver_unregister",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/tty/serial/max310x.c:max310x_uart_init",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:auxiliary_driver_unregister",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/staging/vme_user/vme.c:vme_unregister_driver",
        "drivers/staging/vme_user/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590978672,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498987160,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_driver_unregister",
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/amba/bus.c:amba_driver_unregister",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/mfd/stmpe-spi.c:stmpe_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/firmware/arm_scmi/bus.c:scmi_driver_unregister",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498987160,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231555776,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/amba/bus.c:amba_driver_unregister",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/mfd/stmpe-spi.c:stmpe_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/firmware/arm_scmi/bus.c:scmi_driver_unregister",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231555776,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292140176,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/vio.c:vio_unregister_driver",
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/mfd/stmpe-spi.c:stmpe_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292140176,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276362912,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/mfd/stmpe-spi.c:stmpe_exit",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/mmc/host/mmc_spi.c:mmc_spi_driver_exit",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276362912,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585948640,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948640,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585797696,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/nvdimm/pmem.c:nd_pmem_driver_exit",
        "drivers/nvdimm/blk.c:nd_blk_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/dax/pmem/pmem.c:dax_pmem_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/hv/vmbus_drv.c:vmbus_driver_unregister",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797696,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586138288,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586138288,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void driver_unregister(struct device_driver * drv)
```

```json
{
  "name": "driver_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586246976,
      "name": "driver_unregister",
      "external": true,
      "loc": "drivers/base/driver.c:190",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver",
        "drivers/rapidio/rio-driver.c:rio_unregister_driver",
        "drivers/acpi/bus.c:acpi_bus_unregister_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_exit",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_unregister_driver",
        "drivers/virtio/virtio.c:unregister_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver",
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/base/platform.c:platform_unregister_drivers",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_exit",
        "drivers/mfd/da9052-spi.c:da9052_spi_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/dimm.c:nvdimm_exit",
        "drivers/nvdimm/region.c:nd_region_exit",
        "drivers/dax/bus.c:dax_driver_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister",
        "drivers/spi/spi-mem.c:spi_mem_driver_unregister",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_exit",
        "drivers/net/phy/phy_device.c:phy_init",
        "drivers/net/phy/phy_device.c:phy_drivers_unregister",
        "drivers/net/phy/phy_device.c:phy_drivers_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_unregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister_device_driver",
        "drivers/input/serio/serio.c:serio_unregister_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_unregister",
        "drivers/mmc/core/bus.c:mmc_unregister_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_driver",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246976,
      "name": "driver_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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

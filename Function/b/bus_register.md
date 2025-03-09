# Function: <code>bus_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584392784,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:888",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_register",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584392784,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584727872,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:887",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_register",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584727872,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584917664,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:887",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_register",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917664,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585002784,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:846",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_register",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002784,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585424720,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:846",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_register",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424720,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667632,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:844",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667632,
      "name": "bus_register",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585797328,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:851",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797328,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586030256,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:825",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/soundwire/bus_type.c:sdw_bus_init",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586030256,
      "name": "bus_register",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586177632,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:801",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586177632,
      "name": "bus_register",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586938288,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:802",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938288,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 969
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587023568,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:802",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/auxiliary.c:auxiliary_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023568,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586907200,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:785",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/auxiliary.c:auxiliary_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586907200,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587468896,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:781",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/auxiliary.c:auxiliary_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468896,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588789360,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:783",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/auxiliary.c:auxiliary_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588789360,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 963
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590284672,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:783",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/auxiliary.c:auxiliary_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/staging/vme_user/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590284672,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
int bus_register(const struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590604928,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:844",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/auxiliary.c:auxiliary_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/soc.c:soc_bus_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/staging/vme_user/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590604928,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
int bus_register(const struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590963920,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:844",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/auxiliary.c:auxiliary_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/soc.c:soc_bus_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/staging/vme_user/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590963920,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 847
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498974184,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:801",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_driver_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/amba/bus.c:amba_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/power/domain.c:genpd_bus_init",
        "drivers/base/soc.c:soc_bus_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/mmc/core/block.c:mmc_blk_init",
        "drivers/firmware/arm_scmi/bus.c:scmi_bus_init",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498974184,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231543564,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:801",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/amba/bus.c:amba_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/power/domain.c:genpd_bus_init",
        "drivers/base/soc.c:soc_bus_register",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/mmc/core/block.c:mmc_blk_init",
        "drivers/firmware/arm_scmi/bus.c:scmi_bus_init",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init",
        "sound/ac97_bus.c:ac97_bus_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231543564,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292123856,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:801",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/vio.c:vio_bus_init",
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/power/domain.c:genpd_bus_init",
        "drivers/base/soc.c:soc_bus_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292123856,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276353438,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:801",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/power/domain.c:genpd_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/mmc/core/block.c:mmc_blk_init",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276353438,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585938000,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:801",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585938000,
      "name": "bus_register",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585787136,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:801",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/hv/vmbus_drv.c:hv_acpi_init",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585787136,
      "name": "bus_register",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586127648,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:801",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586127648,
      "name": "bus_register",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int bus_register(struct bus_type * bus)
```

```json
{
  "name": "bus_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586236256,
      "name": "bus_register",
      "external": true,
      "loc": "drivers/base/bus.c:801",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_sysfs_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/pci-driver.c:pci_driver_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/pnp/core.c:pnp_init",
        "drivers/virtio/virtio.c:virtio_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/tty/serdev/core.c:serdev_init",
        "drivers/base/bus.c:subsys_virtual_register",
        "drivers/base/bus.c:subsys_system_register",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/eisa/eisa-bus.c:eisa_init",
        "drivers/mmc/core/bus.c:mmc_register_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_register_bus",
        "drivers/vme/vme.c:vme_init",
        "drivers/nvmem/core.c:nvmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586236256,
      "name": "bus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bus_type * bus</code> ➡️ <code>const struct bus_type * bus</code>
</li>
</ul>
</details>
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

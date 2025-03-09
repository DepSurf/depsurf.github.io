# Function: <code>driver_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584401600,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:148",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584401600,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584736944,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:148",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/isa.c:isa_register_driver",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736944,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584926816,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:148",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/isa.c:isa_register_driver",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584926816,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585011600,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:148",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011600,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585433840,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:148",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433840,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677284,
      "name": "driver_register.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071585676944,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807540,
      "name": "driver_register.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071585807200,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586040772,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071586040416,
      "name": "driver_register",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586188407,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071586188032,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:147",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/nvdimm/bus.c:__nd_driver_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950119,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586949824,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:147",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:__auxiliary_driver_register",
        "drivers/nvdimm/bus.c:__nd_driver_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591486605,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071587034896,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:147",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:__auxiliary_driver_register",
        "drivers/nvdimm/bus.c:__nd_driver_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430285,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071586918688,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:147",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/virtio/virtio.c:register_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:__auxiliary_driver_register",
        "drivers/nvdimm/bus.c:__nd_driver_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592489423,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071587481104,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:216",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/virtio/virtio.c:register_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:__auxiliary_driver_register",
        "drivers/nvdimm/bus.c:__nd_driver_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594359075,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071588802656,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590299552,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:222",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/virtio/virtio.c:register_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:__auxiliary_driver_register",
        "drivers/nvdimm/bus.c:__nd_driver_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/staging/vme_user/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299552,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590619248,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:222",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/virtio/virtio.c:register_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serial/serial_base_bus.c:serial_base_driver_register",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:__auxiliary_driver_register",
        "drivers/nvdimm/bus.c:__nd_driver_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/staging/vme_user/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590619248,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590978352,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:222",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/virtio/virtio.c:register_virtio_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serial/serial_base_bus.c:serial_base_driver_register",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/auxiliary.c:__auxiliary_driver_register",
        "drivers/nvdimm/bus.c:__nd_driver_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/staging/vme_user/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590978352,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498986824,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/fsl-mc-bus.c:__fsl_mc_driver_register",
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/amba/bus.c:amba_driver_register",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498986824,
      "name": "driver_register",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231555452,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/amba/bus.c:amba_driver_register",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231555452,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292139680,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/vio.c:__vio_register_driver",
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/virtio/virtio.c:register_virtio_driver",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292139680,
      "name": "driver_register",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276362628,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276362628,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948775,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585948400,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/hv/vmbus_drv.c:__vmbus_driver_register",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797831,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585797456,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586138423,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071586138048,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int driver_register(struct device_driver * drv)
```

```json
{
  "name": "driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "driver_register",
      "external": true,
      "loc": "drivers/base/driver.c:146",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:__pci_register_driver",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_service_register",
        "drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver",
        "drivers/rapidio/rio-driver.c:rio_register_driver",
        "drivers/acpi/bus.c:acpi_bus_register_driver",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/pnp/driver.c:pnp_register_driver",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common",
        "drivers/tty/serdev/core.c:__serdev_device_driver_register",
        "drivers/base/platform.c:__platform_register_drivers",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:__dax_driver_register",
        "drivers/scsi/scsi_sysfs.c:scsi_register_driver",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full",
        "drivers/spi/spi.c:__spi_register_driver",
        "drivers/net/phy/phy_device.c:phy_driver_register",
        "drivers/net/phy/mdio_device.c:mdio_driver_register",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/input/serio/serio.c:__serio_register_driver",
        "drivers/eisa/eisa-bus.c:eisa_driver_register",
        "drivers/mmc/core/bus.c:mmc_register_driver",
        "drivers/mmc/core/sdio_bus.c:sdio_register_driver",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586247111,
      "name": "driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071586246736,
      "name": "driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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

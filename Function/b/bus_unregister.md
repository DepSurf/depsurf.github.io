# Function: <code>bus_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584392448,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:973",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_unregister",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core.c:i2c_exit",
        "drivers/edac/edac_stub.c:edac_put_sysfs_subsys",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/vme/vme.c:vme_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584392448,
      "name": "bus_unregister",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584727360,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:972",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_unregister",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core.c:i2c_exit",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/vme/vme.c:vme_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584727360,
      "name": "bus_unregister",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584917152,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:972",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_unregister",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core.c:i2c_exit",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917152,
      "name": "bus_unregister",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585002352,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:931",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002352,
      "name": "bus_unregister",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585424288,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:931",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_unregister",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424288,
      "name": "bus_unregister",
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
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667200,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:929",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667200,
      "name": "bus_unregister",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585796896,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:936",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796896,
      "name": "bus_unregister",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586029808,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:910",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/soundwire/bus_type.c:sdw_bus_exit",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586029808,
      "name": "bus_unregister",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586177184,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:886",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586177184,
      "name": "bus_unregister",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937712,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:887",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937712,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587022992,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:887",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587022992,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586906624,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:870",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586906624,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587468320,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:866",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468320,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588788752,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:868",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588788752,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590284032,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:868",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590284032,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
void bus_unregister(const struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590604336,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:929",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serial/serial_base_bus.c:serial_base_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590604336,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void bus_unregister(const struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590963280,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:929",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serial/serial_base_bus.c:serial_base_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590963280,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498974768,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:886",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_driver_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/mmc/core/block.c:mmc_blk_exit",
        "drivers/mmc/core/block.c:mmc_blk_init",
        "drivers/firmware/arm_scmi/bus.c:scmi_bus_exit",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498974768,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231544144,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:886",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/mmc/core/block.c:mmc_blk_exit",
        "drivers/mmc/core/block.c:mmc_blk_init",
        "drivers/firmware/arm_scmi/bus.c:scmi_bus_exit",
        "drivers/nvmem/core.c:nvmem_exit",
        "sound/ac97_bus.c:ac97_bus_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231544144,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292123168,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:886",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/suspend.c:__machine_initcall_pseries_pseries_suspend_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292123168,
      "name": "bus_unregister",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276352946,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:886",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/mmc/core/block.c:mmc_blk_exit",
        "drivers/mmc/core/block.c:mmc_blk_init",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276352946,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585937552,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:886",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585937552,
      "name": "bus_unregister",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585786688,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:886",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/hv/vmbus_drv.c:vmbus_exit",
        "drivers/hv/vmbus_drv.c:hv_acpi_init",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585786688,
      "name": "bus_unregister",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586127200,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:886",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586127200,
      "name": "bus_unregister",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type * bus)
```

```json
{
  "name": "bus_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235808,
      "name": "bus_unregister",
      "external": true,
      "loc": "drivers/base/bus.c:886",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit",
        "drivers/virtio/virtio.c:virtio_exit",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/serdev/core.c:serdev_exit",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/edac/edac_module.c:edac_exit",
        "drivers/edac/edac_module.c:edac_init",
        "drivers/mmc/core/bus.c:mmc_unregister_bus",
        "drivers/mmc/core/sdio_bus.c:sdio_unregister_bus",
        "drivers/nvmem/core.c:nvmem_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235808,
      "name": "bus_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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

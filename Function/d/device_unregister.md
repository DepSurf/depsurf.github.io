# Function: <code>device_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584378928,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:1296",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/video/backlight/backlight.c:backlight_device_unregister",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_destroy",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/nvdimm/core.c:nvdimm_bus_unregister",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/spi/spi.c:__unregister",
        "drivers/spi/spi.c:spi_unregister_master",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/i2c/i2c-core.c:__unregister_dummy",
        "drivers/i2c/i2c-core.c:__unregister_client",
        "drivers/i2c/i2c-core.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core.c:i2c_sysfs_delete_device",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_dev_release",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/extcon/extcon.c:extcon_dev_unregister",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378928,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584713904,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:1296",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_unregister",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_destroy",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/isa.c:isa_register_driver",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_master",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core.c:i2c_unregister_device",
        "drivers/i2c/i2c-core.c:i2c_unregister_device",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_dev_release",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/extcon/extcon.c:extcon_dev_unregister",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713904,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584905072,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:1887",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_unregister",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_destroy",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/isa.c:isa_register_driver",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_master",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core.c:i2c_unregister_device",
        "drivers/i2c/i2c-core.c:i2c_unregister_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_dev_release",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/extcon/extcon.c:extcon_dev_unregister",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584905072,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584990304,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:1885",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:of_led_classdev_register",
        "drivers/devfreq/devfreq.c:devm_devfreq_dev_release",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584990304,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585412256,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2020",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:of_led_classdev_register",
        "drivers/devfreq/devfreq.c:devm_devfreq_dev_release",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412256,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585654176,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2067",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:of_led_classdev_register",
        "drivers/devfreq/devfreq.c:devm_devfreq_dev_release",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585654176,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585783728,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2142",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:of_led_classdev_register",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585783728,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586014096,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2368",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:of_led_classdev_register",
        "drivers/soundwire/bus.c:sdw_delete_slave",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586014096,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161616,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2405",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161616,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919568,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2906",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_unregister",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_unregister",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devm_devfreq_dev_release",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone",
        "drivers/nvmem/core.c:nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919568,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587004000,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:3318",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_unregister",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:__device_link_del",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/roles/class.c:usb_role_switch_unregister",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_unregister",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone",
        "drivers/nvmem/core.c:nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004000,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586886512,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:3545",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_unregister",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:__device_link_del",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/roles/class.c:usb_role_switch_unregister",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_unregister",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone",
        "drivers/nvmem/core.c:nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586886512,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587448528,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:3610",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_unregister",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:__device_link_del",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/roles/class.c:usb_role_switch_unregister",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_unregister",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_release",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone",
        "drivers/nvmem/core.c:nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587448528,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588766112,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:3644",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_unregister",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:__device_link_del",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:remove_memory_block",
        "drivers/base/memory.c:add_memory_block",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/roles/class.c:usb_role_switch_unregister",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_unregister",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_release",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone",
        "drivers/nvmem/core.c:nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588766112,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590257248,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:3843",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_unregister",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:__device_link_del",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:remove_memory_block",
        "drivers/base/memory.c:add_memory_block",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/roles/class.c:usb_role_switch_unregister",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/staging/vme_user/vme.c:vme_unregister_driver",
        "drivers/staging/vme_user/vme.c:__vme_register_driver_bus",
        "drivers/staging/vme_user/vme.c:__vme_register_driver_bus",
        "drivers/staging/vme_user/vme.c:vme_unregister_bridge",
        "drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_unregister",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_release",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone",
        "drivers/nvmem/core.c:nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590257248,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590576512,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:3852",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_unregister",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:__device_link_del",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_unregister",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:remove_memory_block",
        "drivers/base/memory.c:add_memory_block",
        "drivers/base/soc.c:soc_device_unregister",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/dax/bus.c:unregister_dax_mapping",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/roles/class.c:usb_role_switch_unregister",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/staging/vme_user/vme.c:vme_unregister_driver",
        "drivers/staging/vme_user/vme.c:__vme_register_driver_bus",
        "drivers/staging/vme_user/vme.c:__vme_register_driver_bus",
        "drivers/staging/vme_user/vme.c:vme_unregister_bridge",
        "drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_unregister",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_release",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone",
        "drivers/nvmem/core.c:nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590576512,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590934912,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:3866",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_unregister",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:__device_link_del",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:arch_unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_unregister",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:remove_memory_block",
        "drivers/base/memory.c:add_memory_block",
        "drivers/base/soc.c:soc_device_unregister",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/dax/bus.c:unregister_dax_mapping",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_sysfs.c:drm_class_device_unregister",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_remove",
        "drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_unregister",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/staging/vme_user/vme.c:vme_unregister_driver",
        "drivers/staging/vme_user/vme.c:__vme_register_driver_bus",
        "drivers/staging/vme_user/vme.c:__vme_register_driver_bus",
        "drivers/staging/vme_user/vme.c:vme_unregister_bridge",
        "drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_unregister",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_release",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone",
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590934912,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498957240,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2405",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/bus/vexpress-config.c:vexpress_config_bridge_register",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/amba/bus.c:amba_device_unregister",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/power/domain.c:genpd_dev_pm_detach",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/base/soc.c:soc_device_unregister",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/roles/class.c:usb_role_switch_unregister",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/firmware/arm_scmi/bus.c:scmi_device_destroy",
        "drivers/of/device.c:of_device_unregister",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498957240,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231528452,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2405",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/bus/vexpress-config.c:vexpress_config_bridge_register",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/amba/bus.c:amba_device_unregister",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/power/domain.c:genpd_dev_pm_detach",
        "drivers/base/soc.c:soc_device_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/mtd/mtdcore.c:del_mtd_device",
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_setup",
        "drivers/usb/gadget/udc/core.c:usb_del_gadget_udc",
        "drivers/usb/gadget/udc/core.c:usb_del_gadget_udc",
        "drivers/usb/roles/class.c:usb_role_switch_unregister",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/firmware/arm_scmi/bus.c:scmi_device_destroy",
        "drivers/of/device.c:of_device_unregister",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone",
        "sound/soc/soc-core.c:soc_cleanup_card_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231528452,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292100848,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2405",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/pci_dlpar.c:remove_phb_dynamic",
        "arch/powerpc/platforms/pseries/vio.c:vio_unregister_device",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/power/domain.c:genpd_dev_pm_detach",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/base/soc.c:soc_device_unregister",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/of/device.c:of_device_unregister",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292100848,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276339172,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2405",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/domain.c:genpd_dev_pm_detach",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/of/device.c:of_device_unregister",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276339172,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585921984,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2405",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585921984,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585771120,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2405",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:slave_store",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/hv/vmbus_drv.c:vmbus_device_unregister",
        "drivers/hv/vmbus_drv.c:vmbus_device_register",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771120,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586111632,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2405",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111632,
      "name": "device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void device_unregister(struct device * dev)
```

```json
{
  "name": "device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586220240,
      "name": "device_unregister",
      "external": true,
      "loc": "drivers/base/core.c:2405",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:destroy_workqueue",
        "mm/backing-dev.c:bdi_unregister",
        "block/bsg.c:bsg_register_queue",
        "drivers/phy/phy-core.c:devm_phy_consume",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus",
        "drivers/pci/pcie/portdrv_core.c:remove_iter",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/acpi/container.c:container_device_detach",
        "drivers/pnp/core.c:__pnp_remove_device",
        "drivers/pnp/core.c:pnp_unregister_protocol",
        "drivers/pnp/card.c:pnp_remove_card",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/pcpu.c:xen_sync_pcpus",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove",
        "drivers/base/core.c:device_destroy",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:unregister_cpu",
        "drivers/base/attribute_container.c:attribute_container_remove_device",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/cacheinfo.c:cpu_cache_sysfs_exit",
        "drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove",
        "drivers/base/isa.c:isa_unregister_driver",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/node.c:unregister_node",
        "drivers/base/memory.c:unregister_memory",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_unregister",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:slave_store",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/core/endpoint.c:usb_remove_ep_devs",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit",
        "drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs",
        "drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev",
        "drivers/vme/vme.c:vme_unregister_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/vme/vme.c:vme_unregister_bridge",
        "drivers/powercap/powercap_sys.c:powercap_unregister_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586220240,
      "name": "device_unregister",
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

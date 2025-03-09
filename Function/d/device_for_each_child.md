# Function: <code>device_for_each_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584377280,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:1387",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_mmio_enabled",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_error_detected",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/pci/pcie/aer/aerdrv_core.c:do_recovery",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/base/core.c:device_offline",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/core.c:nvdimm_bus_unregister",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/spi/spi.c:spi_unregister_master",
        "drivers/i2c/i2c-core.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core.c:i2c_clients_command",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377280,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584712256,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:1387",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_mmio_enabled",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_error_detected",
        "drivers/pci/pcie/aer/aerdrv_core.c:do_recovery",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_offline",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_master",
        "drivers/i2c/i2c-core.c:i2c_clients_command",
        "drivers/i2c/i2c-core.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584712256,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584899616,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:1978",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_mmio_enabled",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_error_detected",
        "drivers/pci/pcie/aer/aerdrv_core.c:do_recovery",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_offline",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/core.c:device_is_dependent",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_master",
        "drivers/i2c/i2c-core.c:i2c_clients_command",
        "drivers/i2c/i2c-core.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584899616,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584985232,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:1976",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_mmio_enabled",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_error_detected",
        "drivers/pci/pcie/aer/aerdrv_core.c:do_recovery",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584985232,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585407056,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2111",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/pci/pcie/aer/aerdrv_core.c:do_recovery",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585407056,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585649376,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2158",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649376,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585778800,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2233",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778800,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586011728,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2459",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/soundwire/bus.c:sdw_delete_bus_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586011728,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586158656,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2496",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158656,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586926985,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2997",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_reorder_to_tail"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586916384,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587010681,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:3409",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_reorder_to_tail"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587000960,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586893929,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:3636",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_reorder_to_tail"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586883312,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587455833,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:3701",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_reorder_to_tail"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444912,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588774713,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:3735",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/core.c:device_is_dependent"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/acpi/bus.c:acpi_dev_for_each_child",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761664,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590267801,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:3934",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/core.c:device_is_dependent"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_port_runtime_suspend",
        "drivers/pci/pcie/portdrv.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_suspend",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/acpi/bus.c:acpi_dev_for_each_child",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590250496,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590588201,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:3943",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/core.c:device_is_dependent"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_port_runtime_suspend",
        "drivers/pci/pcie/portdrv.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_suspend",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/acpi/bus.c:acpi_dev_for_each_child",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/scsi/scsi_lib.c:scsi_block_targets",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590570528,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590946873,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:3956",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/core.c:device_is_dependent"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_port_runtime_suspend",
        "drivers/pci/pcie/portdrv.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv.c:pcie_port_device_suspend",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/acpi/bus.c:acpi_dev_for_each_child",
        "drivers/pmdomain/governor.c:default_suspend_ok",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/scsi/scsi_lib.c:scsi_block_targets",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590928928,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498953336,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2496",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/hisi_lpc.c:hisi_lpc_acpi_remove",
        "drivers/bus/fsl-mc/dprc-driver.c:dprc_scan_objects",
        "drivers/bus/fsl-mc/dprc-driver.c:dprc_scan_objects",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498953336,
      "name": "device_for_each_child",
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231524776,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2496",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_remove",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231524776,
      "name": "device_for_each_child",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292095776,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2496",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/scsi/scsi_transport_srp.c:srp_remove_host",
        "drivers/scsi/scsi_transport_srp.c:srp_timed_out",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292095776,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276336114,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2496",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276336114,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585919024,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2496",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585919024,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585768160,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2496",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768160,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586108672,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2496",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586108672,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int device_for_each_child(struct device * parent, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "device_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586217280,
      "name": "device_for_each_child",
      "external": true,
      "loc": "drivers/base/core.c:2496",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_device",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_find_service",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume",
        "drivers/rapidio/rio.c:rio_unregister_mport",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_exit",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_get",
        "drivers/base/core.c:device_reorder_to_tail",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/domain_governor.c:default_suspend_ok",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/da903x.c:da903x_remove",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:flush_regions_dimms",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:nd_ns_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/scsi/scsi_lib.c:scsi_target_unblock",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/i2c/i2c-core-base.c:i2c_clients_command",
        "drivers/i2c/i2c-core-base.c:i2c_check_addr_busy",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-core-base.c:i2c_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586217280,
      "name": "device_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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

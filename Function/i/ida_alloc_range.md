# Function: <code>ida_alloc_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589366000,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:377",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589366000,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:388",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589824078,
      "name": "ida_alloc_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589823136,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 942
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590049120,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:379",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590049120,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585043456,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:379",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:memcg_alloc_cache_id",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:__blk_alloc_queue",
        "lib/memregion.c:memregion_alloc",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_alloc",
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585043456,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585195184,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:380",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:memcg_online_kmem",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue",
        "lib/memregion.c:memregion_alloc",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_alloc",
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585195184,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585078272,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:380",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:memcg_online_kmem",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue",
        "lib/memregion.c:memregion_alloc",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_alloc",
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585078272,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1030
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585525120,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:380",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:memcg_online_kmem",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "lib/memregion.c:memregion_alloc",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_alloc",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585525120,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1073
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586678352,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:380",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-core.c:blk_alloc_queue",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "lib/memregion.c:memregion_alloc",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/platform-msi.c:platform_msi_alloc_priv_data",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/net/wwan/wwan_core.c:wwan_create_port",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_alloc",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586678352,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1081
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595758592,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:380",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "kernel/trace/trace_output.c:register_trace_event",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "lib/memregion.c:memregion_alloc",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/platform-msi.c:platform_msi_alloc_priv_data",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/net/wwan/wwan_core.c:wwan_create_port",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_alloc",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595758592,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596282928,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:380",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "kernel/trace/trace_output.c:register_trace_event",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "lib/memregion.c:memregion_alloc",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serial/serial_base_bus.c:serial_base_port_add",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/platform-msi.c:platform_msi_alloc_priv_data",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/net/wwan/wwan_core.c:wwan_create_port",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_alloc",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596282928,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1079
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597167648,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:380",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "kernel/trace/trace_output.c:register_trace_event",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "lib/memregion.c:memregion_alloc",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serial/serial_base_bus.c:serial_base_port_add",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/iommu.c:iommu_alloc_global_pasid",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/platform-msi.c:platform_msi_alloc_priv_data",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/gpu/drm/drm_connector.c:__drm_connector_init",
        "drivers/gpu/drm/drm_connector.c:__drm_connector_init",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/nvmem/core.c:nvmem_register",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_alloc",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/core/xdp.c:__xdp_reg_mem_model",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597167648,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1219
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503823896,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:379",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req",
        "drivers/firmware/arm_scmi/bus.c:scmi_device_create",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503823896,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1116
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236445504,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:379",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe",
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req",
        "drivers/firmware/arm_scmi/bus.c:scmi_device_create",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236445504,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297669616,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:379",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/mmu_context.c:init_new_context",
        "arch/powerpc/mm/book3s64/mmu_context.c:hash__alloc_context_id",
        "arch/powerpc/mm/book3s64/mmu_context.c:hash__alloc_context_id",
        "arch/powerpc/mm/book3s64/mmu_context.c:hash__reserve_context_id",
        "arch/powerpc/platforms/powernv/vas-window.c:vas_window_alloc",
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297669616,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1276
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279718998,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:379",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279718998,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 874
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589651376,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:379",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589651376,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589377184,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:379",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589377184,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590094752,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:379",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590094752,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
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
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```

```json
{
  "name": "ida_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590145008,
      "name": "ida_alloc_range",
      "external": true,
      "loc": "lib/idr.c:379",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:invent_group_ids",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/eventfd.c:do_eventfd",
        "fs/proc/generic.c:proc_register",
        "fs/devpts/inode.c:devpts_new_index",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/sock_reuseport.c:reuseport_get_id",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590145008,
      "name": "ida_alloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int ida_alloc_range(struct ida * ida, unsigned int min, unsigned int max, gfp_t gfp)
```
</details>
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

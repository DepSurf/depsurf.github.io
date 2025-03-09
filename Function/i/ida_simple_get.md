# Function: <code>ida_simple_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ida_simple_get(struct ida * ida, unsigned int start, unsigned int end, gfp_t gfp_mask)
```

```json
{
  "name": "ida_simple_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953168,
      "name": "ida_simple_get",
      "external": true,
      "loc": "lib/idr.c:1078",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:memcg_activate_kmem",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/nvdimm/core.c:__nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953168,
      "name": "ida_simple_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int ida_simple_get(struct ida * ida, unsigned int start, unsigned int end, gfp_t gfp_mask)
```

```json
{
  "name": "ida_simple_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240784,
      "name": "ida_simple_get",
      "external": true,
      "loc": "lib/idr.c:1078",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240784,
      "name": "ida_simple_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int ida_simple_get(struct ida * ida, unsigned int start, unsigned int end, gfp_t gfp_mask)
```

```json
{
  "name": "ida_simple_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583356096,
      "name": "ida_simple_get",
      "external": true,
      "loc": "lib/idr.c:1084",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356096,
      "name": "ida_simple_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int ida_simple_get(struct ida * ida, unsigned int start, unsigned int end, gfp_t gfp_mask)
```

```json
{
  "name": "ida_simple_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588204912,
      "name": "ida_simple_get",
      "external": true,
      "loc": "lib/idr.c:425",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588204912,
      "name": "ida_simple_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int ida_simple_get(struct ida * ida, unsigned int start, unsigned int end, gfp_t gfp_mask)
```

```json
{
  "name": "ida_simple_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588753808,
      "name": "ida_simple_get",
      "external": true,
      "loc": "lib/idr.c:433",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588753808,
      "name": "ida_simple_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int ida_simple_get(struct ida * ida, unsigned int start, unsigned int end, gfp_t gfp_mask)
```

```json
{
  "name": "ida_simple_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589132064,
      "name": "ida_simple_get",
      "external": true,
      "loc": "lib/idr.c:563",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/proc/generic.c:proc_register",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/phy/phy-core.c:phy_create",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/platform.c:platform_device_add",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/nvdimm/dimm_devs.c:nvdimm_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_alloc",
        "drivers/nvdimm/dax_devs.c:nd_dax_alloc",
        "drivers/dax/super.c:alloc_dax",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/input/input.c:input_get_new_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132064,
      "name": "ida_simple_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int ida_simple_get(struct ida * ida, unsigned int start, unsigned int end, gfp_t gfp_mask)
```
</details>
</li>
</ul>

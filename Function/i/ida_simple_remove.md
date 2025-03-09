# Function: <code>ida_simple_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ida_simple_remove(struct ida * ida, unsigned int id)
```

```json
{
  "name": "ida_simple_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582953424,
      "name": "ida_simple_remove",
      "external": true,
      "loc": "lib/idr.c:1123",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "kernel/workqueue.c:worker_thread",
        "mm/memcontrol.c:memcg_activate_kmem",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:blk_release_queue",
        "drivers/phy/phy-core.c:phy_release",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform.c:platform_device_del",
        "drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs",
        "drivers/base/platform-msi.c:platform_msi_domain_free_irqs",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/nvdimm/core.c:nvdimm_bus_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/input/input.c:input_free_minor",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953424,
      "name": "ida_simple_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ida_simple_remove(struct ida * ida, unsigned int id)
```

```json
{
  "name": "ida_simple_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241040,
      "name": "ida_simple_remove",
      "external": true,
      "loc": "lib/idr.c:1123",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:blk_release_queue",
        "drivers/phy/phy-core.c:phy_release",
        "drivers/gpio/gpiolib.c:gpiochip_add_data",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_release",
        "drivers/base/platform.c:platform_device_del",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform-msi.c:platform_msi_create_device_domain",
        "drivers/base/platform-msi.c:platform_msi_domain_free_irqs",
        "drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_release",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/input/input.c:input_free_minor",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241040,
      "name": "ida_simple_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ida_simple_remove(struct ida * ida, unsigned int id)
```

```json
{
  "name": "ida_simple_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583356352,
      "name": "ida_simple_remove",
      "external": true,
      "loc": "lib/idr.c:1134",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:blk_release_queue",
        "drivers/phy/phy-core.c:phy_release",
        "drivers/gpio/gpiolib.c:gpiochip_add_data",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_release",
        "drivers/base/platform.c:platform_device_del",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform-msi.c:platform_msi_create_device_domain",
        "drivers/base/platform-msi.c:platform_msi_domain_free_irqs",
        "drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs",
        "drivers/nvdimm/bus.c:nvdimm_bus_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_release",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/input/input.c:input_free_minor",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356352,
      "name": "ida_simple_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ida_simple_remove(struct ida * ida, unsigned int id)
```

```json
{
  "name": "ida_simple_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588205168,
      "name": "ida_simple_remove",
      "external": true,
      "loc": "lib/idr.c:475",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/proc/generic.c:pde_put",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/phy/phy-core.c:phy_release",
        "drivers/gpio/gpiolib.c:gpiochip_add_data",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_release",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform-msi.c:platform_msi_create_device_domain",
        "drivers/base/platform-msi.c:platform_msi_domain_free_irqs",
        "drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs",
        "drivers/nvdimm/bus.c:nvdimm_bus_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_release",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/super.c:dax_i_callback",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/input/input.c:input_free_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/host.c:mmc_host_classdev_release",
        "drivers/nvmem/core.c:nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588205168,
      "name": "ida_simple_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ida_simple_remove(struct ida * ida, unsigned int id)
```

```json
{
  "name": "ida_simple_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588754064,
      "name": "ida_simple_remove",
      "external": true,
      "loc": "lib/idr.c:483",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/proc/generic.c:pde_put",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/phy/phy-core.c:phy_release",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_ctrl_release",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_release",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform-msi.c:platform_msi_create_device_domain",
        "drivers/base/platform-msi.c:platform_msi_domain_free_irqs",
        "drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs",
        "drivers/nvdimm/bus.c:nvdimm_bus_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_release",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/super.c:dax_i_callback",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/input/input.c:input_free_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/host.c:mmc_host_classdev_release",
        "drivers/nvmem/core.c:nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588754064,
      "name": "ida_simple_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ida_simple_remove(struct ida * ida, unsigned int id)
```

```json
{
  "name": "ida_simple_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589132304,
      "name": "ida_simple_remove",
      "external": true,
      "loc": "lib/idr.c:613",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:create_worker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/proc/generic.c:proc_register",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/phy/phy-core.c:phy_release",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/virtio/virtio.c:unregister_virtio_device",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/tty/serdev/core.c:serdev_ctrl_release",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_release",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform-msi.c:platform_msi_create_device_domain",
        "drivers/base/platform-msi.c:platform_msi_domain_free_irqs",
        "drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs",
        "drivers/nvdimm/bus.c:nvdimm_bus_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_release",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_release",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/super.c:dax_i_callback",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/input/input.c:input_free_minor",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/ptp/ptp_clock.c:delete_ptp_clock",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "drivers/mmc/core/host.c:mmc_host_classdev_release",
        "drivers/nvmem/core.c:nvmem_release",
        "net/core/xdp.c:__xdp_mem_allocator_rcu_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132304,
      "name": "ida_simple_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void ida_simple_remove(struct ida * ida, unsigned int id)
```
</details>
</li>
</ul>

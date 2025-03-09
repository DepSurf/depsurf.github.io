# Function: <code>sysfs_remove_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519568,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:142",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:free_module",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:do_md_stop",
        "net/core/dev.c:netdev_adjacent_sysfs_del",
        "net/core/dev.c:__netdev_adjacent_dev_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519568,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581705552,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:142",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705552,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793408,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:142",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793408,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581848400,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:142",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848400,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581998208,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998208,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582186272,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:142",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186272,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582281424,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281424,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446128,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446128,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545312,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545312,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582851696,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:acpi_pss_perf_init",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:unlink_peers",
        "drivers/usb/core/port.c:unlink_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_del_links",
        "net/core/dev.c:netdev_adjacent_del_links",
        "net/core/dev.c:netdev_adjacent_del_links",
        "net/core/dev.c:netdev_adjacent_del_links",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582851696,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582924688,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:acpi_pss_perf_init",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/regulator/core.c:destroy_regulator",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:unlink_peers",
        "drivers/usb/core/port.c:unlink_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_del_links",
        "net/core/dev.c:netdev_adjacent_del_links",
        "net/core/dev.c:netdev_adjacent_del_links",
        "net/core/dev.c:netdev_adjacent_del_links",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924688,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952336,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952336,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583287568,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_unregister_queue",
        "block/holder.c:bd_register_pending_holders",
        "block/holder.c:bd_register_pending_holders",
        "block/holder.c:bd_register_pending_holders",
        "block/holder.c:bd_unlink_disk_holder",
        "block/holder.c:bd_unlink_disk_holder",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583287568,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583793488,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_unregister_queue",
        "block/holder.c:bd_register_pending_holders",
        "block/holder.c:bd_register_pending_holders",
        "block/holder.c:bd_register_pending_holders",
        "block/holder.c:bd_unlink_disk_holder",
        "block/holder.c:bd_unlink_disk_holder",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:connector_unbind",
        "drivers/usb/core/port.c:connector_unbind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583793488,
      "name": "sysfs_remove_link",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584413408,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_unregister_queue",
        "block/holder.c:bd_unlink_disk_holder",
        "block/holder.c:bd_unlink_disk_holder",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_init",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:connector_unbind",
        "drivers/usb/core/port.c:connector_unbind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584413408,
      "name": "sysfs_remove_link",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584641968,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_unregister_queue",
        "block/holder.c:bd_unlink_disk_holder",
        "block/holder.c:bd_unlink_disk_holder",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_init",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:__iommu_group_release_device",
        "drivers/iommu/iommu.c:__iommu_group_release_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:connector_unbind",
        "drivers/usb/core/port.c:connector_unbind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584641968,
      "name": "sysfs_remove_link",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584874304,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_alias",
        "mm/slub.c:sysfs_slab_add",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_unregister_queue",
        "block/holder.c:bd_unlink_disk_holder",
        "block/holder.c:bd_unlink_disk_holder",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_init",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/iommu/iommu.c:iommu_group_alloc_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_remove_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_remove_early",
        "drivers/gpu/drm/drm_sysfs.c:typec_connector_unbind",
        "drivers/gpu/drm/drm_sysfs.c:typec_connector_unbind",
        "drivers/gpu/drm/drm_sysfs.c:typec_connector_bind",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:connector_unbind",
        "drivers/usb/core/port.c:connector_unbind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_unbind_cdev_from_trip",
        "drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_remove",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584874304,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494183528,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494183528,
      "name": "sysfs_remove_link",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227620692,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227620692,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287871680,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:sysfs_remove_device_from_node",
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287871680,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273647914,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273647914,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514048,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/nvme/host/core.c:nvme_free_ctrl",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514048,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451216,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/scsi_transport_fc.c:fc_vport_terminate",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/nvme/host/core.c:nvme_free_ctrl",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451216,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504528,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504528,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sysfs_remove_link(struct kobject * kobj, const char * name)
```

```json
{
  "name": "sysfs_remove_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585136,
      "name": "sysfs_remove_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:143",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:del_usage_links",
        "mm/slub.c:sysfs_slab_add",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_unlink_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "drivers/pci/slot.c:pci_hp_remove_module_link",
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu-sysfs.c:iommu_device_unlink",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:root_device_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/core.c:device_remove_class_symlinks",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_remove_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/module.c:module_remove_driver",
        "drivers/base/module.c:module_remove_driver",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585136,
      "name": "sysfs_remove_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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

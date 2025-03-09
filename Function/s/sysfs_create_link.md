# Function: <code>sysfs_create_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519968,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:add_disk",
        "block/genhd.c:add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:md_run",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519968,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581705952,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705952,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793808,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793808,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581848816,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848816,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581998624,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998624,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582186704,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:88",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186704,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582281840,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281840,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446512,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446512,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545712,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545712,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582852096,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:register_disk",
        "block/genhd.c:register_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:acpi_pss_perf_init",
        "drivers/acpi/processor_driver.c:acpi_pss_perf_init",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_add_links",
        "net/core/dev.c:netdev_adjacent_add_links",
        "net/core/dev.c:netdev_adjacent_add_links",
        "net/core/dev.c:netdev_adjacent_add_links",
        "net/core/dev.c:__netdev_adjacent_dev_insert",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582852096,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582925088,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:register_disk",
        "block/genhd.c:register_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:acpi_pss_perf_init",
        "drivers/acpi/processor_driver.c:acpi_pss_perf_init",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_add_links",
        "net/core/dev.c:netdev_adjacent_add_links",
        "net/core/dev.c:netdev_adjacent_add_links",
        "net/core/dev.c:netdev_adjacent_add_links",
        "net/core/dev.c:__netdev_adjacent_dev_insert",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582925088,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952736,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:register_disk",
        "block/genhd.c:register_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_device_register",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_insert",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952736,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583287968,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "block/holder.c:bd_register_pending_holders",
        "block/holder.c:bd_register_pending_holders",
        "block/holder.c:bd_link_disk_holder",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/firmware/edd.c:edd_device_register",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_insert",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583287968,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583793408,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "block/holder.c:bd_register_pending_holders",
        "block/holder.c:bd_register_pending_holders",
        "block/holder.c:bd_link_disk_holder",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/firmware/edd.c:edd_device_register",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_insert",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583793408,
      "name": "sysfs_create_link",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584413312,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "block/holder.c:bd_link_disk_holder",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_init",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_init",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_insert",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584413312,
      "name": "sysfs_create_link",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584641872,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "block/holder.c:bd_link_disk_holder",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_init",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_init",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_insert",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584641872,
      "name": "sysfs_create_link",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584874208,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_alias",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "block/holder.c:bd_link_disk_holder",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/pci/iov.c:pci_iov_sysfs_link",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_init",
        "drivers/acpi/processor_thermal.c:acpi_processor_thermal_init",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/iommu/iommu.c:iommu_group_alloc_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/core.c:devlink_add_symlinks",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/gpu/drm/drm_drv.c:drm_dev_register",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add_late",
        "drivers/gpu/drm/drm_sysfs.c:typec_connector_bind",
        "drivers/gpu/drm/drm_sysfs.c:typec_connector_bind",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:connector_bind",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:netdev_adjacent_rename_links",
        "net/core/dev.c:__netdev_adjacent_dev_insert",
        "net/core/dev.c:__netdev_adjacent_dev_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584874208,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494184160,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494184160,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227620556,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227620556,
      "name": "sysfs_create_link",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287872464,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:sysfs_add_device_to_node",
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287872464,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273648380,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273648380,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514448,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/nvme/host/core.c:nvme_init_subsystem",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514448,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451616,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/scsi/scsi_transport_fc.c:fc_vport_setup",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/nvme/host/core.c:nvme_init_subsystem",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451616,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504928,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504928,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sysfs_create_link(struct kobject * kobj, struct kobject * target, const char * name)
```

```json
{
  "name": "sysfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585552,
      "name": "sysfs_create_link",
      "external": true,
      "loc": "fs/sysfs/symlink.c:89",
      "file": "fs/sysfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_setup",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/slot.c:pci_hp_create_module_link",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/class.c:class_compat_create_link",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_powers",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink",
        "drivers/firmware/edd.c:edd_init",
        "net/core/dev.c:netdev_adjacent_sysfs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585552,
      "name": "sysfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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

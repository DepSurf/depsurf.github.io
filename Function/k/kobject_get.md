# Function: <code>kobject_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582955152,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:591",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_get",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_register_disk",
        "block/genhd.c:get_disk",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955152,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242736,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:591",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_add",
        "fs/char_dev.c:cdev_get",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_register_disk",
        "block/genhd.c:get_disk",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242736,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583358048,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:591",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_add",
        "fs/char_dev.c:cdev_get",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_register_dev",
        "block/genhd.c:get_disk",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/class.c:__class_register",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583358048,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588208272,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:591",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/char_dev.c:cdev_get",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/blk-core.c:blk_init_rl",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208272,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588757824,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:591",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/char_dev.c:cdev_get",
        "fs/block_dev.c:bd_link_disk_holder",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757824,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589135968,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:606",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/char_dev.c:cdev_get",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589135968,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589370816,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:606",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/char_dev.c:cdev_get",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589370816,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589827664,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:637",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/char_dev.c:cdev_get",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589827664,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590053808,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:637",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590053808,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585049168,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:655",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_get_by_id",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_block",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585049168,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585198960,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:652",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_get_by_id",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:__fw_devlink_link_to_suppliers",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_block",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585198960,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585082032,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:652",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_get_by_id",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:fw_devlink_link_device",
        "drivers/base/core.c:__fw_devlink_link_to_suppliers",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585082032,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585528976,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:652",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "fs/char_dev.c:cdev_add",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/holder.c:bd_link_disk_holder",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_bus_notifier",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_page_response",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_get_by_id",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:__fw_devlink_link_to_suppliers",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528976,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586682816,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:620",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "fs/char_dev.c:cdev_add",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/holder.c:bd_link_disk_holder",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_get_by_id",
        "drivers/iommu/iommu.c:iommu_probe_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:__fw_devlink_link_to_suppliers",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586682816,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595763536,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:628",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "fs/char_dev.c:cdev_add",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/iommu/iommu.c:iommu_device_release_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_claim_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_get_by_id",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_any_child",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:get_device",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:__fw_devlink_relax_cycles",
        "drivers/base/core.c:__fw_devlink_relax_cycles",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595763536,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596287936,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:629",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "fs/char_dev.c:cdev_add",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/iommu/iommu.c:iommu_device_release_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_claim_dma_owner",
        "drivers/iommu/iommu.c:iommu_device_unuse_default_domain",
        "drivers/iommu/iommu.c:iommu_device_use_default_domain",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:probe_iommu_group",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_any_child",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:get_device",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:__fw_devlink_relax_cycles",
        "drivers/base/core.c:__fw_devlink_relax_cycles",
        "drivers/base/core.c:fw_devlink_dev_sync_state",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:bus_to_subsys",
        "drivers/base/class.c:class_to_subsys",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596287936,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597172800,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:636",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "fs/char_dev.c:cdev_add",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/holder.c:bd_link_disk_holder",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:generic_single_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:get_pci_alias_group",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_any_child",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:get_device",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:__fw_devlink_relax_cycles",
        "drivers/base/core.c:__fw_devlink_relax_cycles",
        "drivers/base/core.c:fw_devlink_dev_sync_state",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:bus_to_subsys",
        "drivers/base/class.c:class_to_subsys",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597172800,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503830048,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:637",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/of/dynamic.c:of_changeset_action",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503830048,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236450164,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:637",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/of/dynamic.c:of_changeset_action",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236450164,
      "name": "kobject_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297676944,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:637",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_group_get_by_id",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/of/dynamic.c:of_changeset_action",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297676944,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279722924,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:637",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/of/dynamic.c:of_changeset_action",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279722924,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589656064,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:637",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656064,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589381888,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:637",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589381888,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590099440,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:637",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590099440,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct kobject * kobject_get(struct kobject * kobj)
```

```json
{
  "name": "kobject_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590149904,
      "name": "kobject_get",
      "external": true,
      "loc": "lib/kobject.c:637",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "mm/slub.c:__kmemcg_cache_deactivate_after_rcu",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/char_dev.c:cdev_add",
        "fs/block_dev.c:bd_link_disk_holder",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "block/blk-core.c:blk_get_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "drivers/pci/host-bridge.c:pci_get_host_bridge_device",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_sva_unbind_device",
        "drivers/iommu/iommu.c:iommu_sva_bind_device",
        "drivers/iommu/iommu.c:request_default_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev",
        "drivers/iommu/iommu.c:iommu_detach_device",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_get_for_dev",
        "drivers/iommu/iommu.c:fsl_mc_device_group",
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_or_group",
        "drivers/iommu/iommu.c:iommu_group_ref_get",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_change_owner",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_rename",
        "drivers/base/core.c:device_find_child_by_name",
        "drivers/base/core.c:device_find_child",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:klist_children_get",
        "drivers/base/core.c:device_links_unbind_consumers",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_add",
        "drivers/base/bus.c:subsys_interface_register",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/class.c:class_interface_register",
        "drivers/base/class.c:__class_register",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:software_node_get",
        "drivers/pps/pps.c:pps_cdev_open",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/core/net-sysfs.c:netdev_unregister_kobject",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149904,
      "name": "kobject_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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

# Function: <code>kset_create_and_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582958928,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:936",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:slab_sysfs_init",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/class.c:classes_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582958928,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583246368,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:937",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583246368,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361680,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:937",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361680,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588211888,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:940",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211888,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588761456,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:940",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761456,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589139616,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:960",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589139616,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589374560,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:960",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589374560,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589831696,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:991",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589831696,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590057840,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:991",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590057840,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585052528,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:1008",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585052528,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585202320,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:1005",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202320,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585085392,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:1005",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085392,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585532320,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:1005",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532320,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586686176,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:973",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686176,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595767312,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:988",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595767312,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596291712,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:989",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596291712,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597176576,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:1001",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597176576,
      "name": "kset_create_and_add",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503834120,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:991",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/of/base.c:of_core_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503834120,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236454216,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:991",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/of/base.c:of_core_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236454216,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297684032,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:991",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init",
        "arch/powerpc/platforms/powernv/opal-elog.c:opal_elog_init",
        "arch/powerpc/platforms/powernv/opal-dump.c:opal_platform_dump_init",
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/of/base.c:of_core_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297684032,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279727016,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:991",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/of/base.c:of_core_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279727016,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589660096,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:991",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660096,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589385920,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:991",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/hv/vmbus_drv.c:vmbus_device_register",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589385920,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590103472,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:991",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590103472,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct kset * kset_create_and_add(const char * name, const struct kset_uevent_ops * uevent_ops, struct kobject * parent_kobj)
```

```json
{
  "name": "kset_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590153776,
      "name": "kset_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:991",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "mm/slub.c:slab_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "drivers/pci/slot.c:pci_slot_init",
        "drivers/iommu/iommu.c:iommu_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:buses_init",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:classes_init",
        "drivers/base/swnode.c:software_node_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590153776,
      "name": "kset_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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

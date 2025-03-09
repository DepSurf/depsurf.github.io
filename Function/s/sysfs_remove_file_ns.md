# Function: <code>sysfs_remove_file_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581517456,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:410",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:free_module",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_exit",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/driver.c:driver_remove_file",
        "drivers/base/class.c:class_unregister",
        "drivers/base/class.c:__class_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517456,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581703518,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:416",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/driver.c:driver_remove_file",
        "drivers/base/class.c:class_unregister",
        "drivers/base/class.c:__class_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581703456,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581791374,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:416",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/driver.c:driver_remove_file",
        "drivers/base/class.c:class_unregister",
        "drivers/base/class.c:__class_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791312,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581846478,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:418",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846416,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581996254,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:418",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996192,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582183966,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582183904,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582279134,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:465",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279072,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582443774,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443712,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582542718,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542656,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582848782,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848720,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582921486,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:465",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582921424,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582949198,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:476",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949136,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583284430,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:476",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284368,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583789342,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:486",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module/sysfs.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583789264,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584408606,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:486",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module/sysfs.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408512,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584637150,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:486",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module/sysfs.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637056,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584869310,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:499",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module/sysfs.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_delete_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_device",
        "drivers/devfreq/devfreq.c:devfreq_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869216,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494180328,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_remove",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494180208,
      "name": "sysfs_remove_file_ns",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227617344,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227617268,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287867168,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287867040,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273645442,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273645346,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582511454,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511392,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582448622,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448560,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582501934,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501872,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_remove_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582582542,
      "name": "sysfs_remove_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:464",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files"
      ],
      "caller_func": [
        "kernel/module.c:module_remove_modinfo_attrs",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/bus.c:bus_remove_file",
        "drivers/base/class.c:class_remove_file_ns",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582480,
      "name": "sysfs_remove_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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

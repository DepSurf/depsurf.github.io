# Function: <code>sysfs_create_file_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581518384,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:__class_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/firmware/edd.c:edd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518384,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581704384,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:327",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:__class_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/firmware/edd.c:edd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704384,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581792240,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:327",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "lib/kobject.c:kobject_add_internal",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:__class_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/firmware/edd.c:edd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792240,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581847312,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:329",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847312,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581997120,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:329",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997120,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582184848,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:322",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/edd.c:edd_init",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582184848,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582279984,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:322",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/edd.c:edd_init",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279984,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/edd.c:edd_init",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445339,
      "name": "sysfs_create_file_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582444592,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543680,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init",
        "arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/edd.c:edd_init",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543680,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582850080,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init",
        "arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:module_add_modinfo_attrs",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "lib/kobject.c:create_dir",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_block",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/edd.c:edd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582850080,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582923136,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:322",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:module_add_modinfo_attrs",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "lib/kobject.c:create_dir",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_block",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/edd.c:edd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923136,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582950800,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:333",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "lib/kobject.c:create_dir",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/edd.c:edd_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950800,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583286032,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:333",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "lib/kobject.c:create_dir",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/edd.c:edd_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286032,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583791056,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:345",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module/sysfs.c:module_add_modinfo_attrs",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/edd.c:edd_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583791056,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584410688,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:345",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_builtin_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module/sysfs.c:module_add_modinfo_attrs",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/edd.c:edd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584410688,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584639248,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:345",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_builtin_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module/decompress.c:module_decompress_sysfs_init",
        "kernel/module/sysfs.c:module_add_modinfo_attrs",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/edd.c:edd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584639248,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584871536,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:358",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_builtin_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module/decompress.c:module_decompress_sysfs_init",
        "kernel/module/sysfs.c:module_add_modinfo_attrs",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/acpi/fan_attr.c:acpi_fan_create_attributes",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/edd.c:edd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584871536,
      "name": "sysfs_create_file_ns",
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494181488,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_probe",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494181488,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227618380,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227618380,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287868928,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online",
        "arch/powerpc/kernel/fadump.c:setup_fadump",
        "arch/powerpc/kernel/fadump.c:setup_fadump",
        "arch/powerpc/kernel/fadump.c:setup_fadump",
        "arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init",
        "arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init",
        "arch/powerpc/platforms/powernv/opal-psr.c:opal_psr_init",
        "arch/powerpc/platforms/pseries/power.c:__machine_initcall_pseries_apo_pm_init",
        "arch/powerpc/platforms/pseries/dlpar.c:__machine_initcall_pseries_dlpar_sysfs_init",
        "arch/powerpc/platforms/pseries/mobility.c:__machine_initcall_pseries_mobility_sysfs_init",
        "arch/powerpc/platforms/pseries/mobility.c:__machine_initcall_pseries_mobility_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287868928,
      "name": "sysfs_create_file_ns",
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273646356,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273646356,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512416,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/edd.c:edd_init",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512416,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449584,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/edd.c:edd_init",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449584,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502896,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/edd.c:edd_init",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502896,
      "name": "sysfs_create_file_ns",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject * kobj, const struct attribute * attr, const void * ns)
```

```json
{
  "name": "sysfs_create_file_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583504,
      "name": "sysfs_create_file_ns",
      "external": true,
      "loc": "fs/sysfs/file.c:321",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init",
        "arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "fs/sysfs/file.c:sysfs_create_files",
        "block/elevator.c:elv_register_queue",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_set_name",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:device_create_file",
        "drivers/base/bus.c:bus_create_file",
        "drivers/base/driver.c:driver_create_file",
        "drivers/base/class.c:class_create_file_ns",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/edd.c:edd_init",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583504,
      "name": "sysfs_create_file_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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

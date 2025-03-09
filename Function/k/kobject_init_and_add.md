# Function: <code>kobject_init_and_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582959088,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:429",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/module.c:load_module",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959088,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583246512,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:429",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/module.c:load_module",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583246512,
      "name": "kobject_init_and_add",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361824,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:429",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/module.c:load_module",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361824,
      "name": "kobject_init_and_add",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588212032,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:429",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/module.c:load_module",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588212032,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588761600,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:429",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/module.c:load_module",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761600,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:444",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140483,
      "name": "kobject_init_and_add.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589139344,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:444",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375418,
      "name": "kobject_init_and_add.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589374704,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589832589,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589831856,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058733,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590058000,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_block",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:register_entries",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054217,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585053104,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_block",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:register_entries",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381904,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585202896,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/firmware/edd.c:edd_device_register",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324313,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585085968,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/firmware/edd.c:edd_device_register",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342406,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585532896,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, const struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:432",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/build_utility.c:sugov_init",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-integrity.c:blk_integrity_add",
        "block/blk-crypto-sysfs.c:blk_crypto_sysfs_register",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/firmware/edd.c:edd_device_register",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594203993,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071586686800,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int kobject_init_and_add(struct kobject * kobj, const struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595767952,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:440",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/build_utility.c:sugov_init",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-integrity.c:blk_integrity_add",
        "block/blk-crypto-sysfs.c:blk_crypto_sysfs_register",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595767952,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int kobject_init_and_add(struct kobject * kobj, const struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596292352,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:441",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/build_utility.c:sugov_init",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-crypto-sysfs.c:blk_crypto_sysfs_register",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596292352,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int kobject_init_and_add(struct kobject * kobj, const struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597177312,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:448",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/build_utility.c:sugov_init",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init_sysfs",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-crypto-sysfs.c:blk_crypto_sysfs_register",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instance",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597177312,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503834536,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503834536,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236454380,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236454380,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297684288,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297684288,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279727156,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:locate_module_kobject",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279727156,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660989,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589660256,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/hv/vmbus_drv.c:vmbus_add_channel_kobj",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386813,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589386080,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104365,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590103632,
      "name": "kobject_init_and_add",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int kobject_init_and_add(struct kobject * kobj, struct kobj_type * ktype, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_init_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init_and_add",
      "external": true,
      "loc": "lib/kobject.c:464",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "kernel/params.c:locate_module_kobject",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/module.c:mod_sysfs_setup",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "block/blk-integrity.c:blk_integrity_add",
        "drivers/pci/slot.c:pci_create_slot",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/md/dm-sysfs.c:dm_sysfs_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590154672,
      "name": "kobject_init_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590153936,
      "name": "kobject_init_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobj_type * ktype</code> ➡️ <code>const struct kobj_type * ktype</code>
</li>
</ul>
</details>
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

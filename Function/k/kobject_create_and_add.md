# Function: <code>kobject_create_and_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582958704,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:743",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_init",
        "fs/namespace.c:mnt_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:add_disk",
        "block/genhd.c:add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582958704,
      "name": "kobject_create_and_add",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583246160,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:743",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "fs/namespace.c:mnt_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583246160,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361472,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:743",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "fs/namespace.c:mnt_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361472,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588211680,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:746",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "fs/namespace.c:mnt_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211680,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588761248,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:746",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "fs/namespace.c:mnt_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761248,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:760",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140554,
      "name": "kobject_create_and_add.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071589139936,
      "name": "kobject_create_and_add",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:760",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375382,
      "name": "kobject_create_and_add.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071589374368,
      "name": "kobject_create_and_add",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:791",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589832552,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071589831504,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:791",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058696,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071590057648,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:808",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_node",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:register_disk",
        "block/genhd.c:register_disk",
        "block/partitions/core.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054155,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585052944,
      "name": "kobject_create_and_add",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:805",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_node",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:register_disk",
        "block/genhd.c:register_disk",
        "block/partitions/core.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381842,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585202736,
      "name": "kobject_create_and_add",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:805",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:register_disk",
        "block/genhd.c:register_disk",
        "block/partitions/core.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324251,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585085808,
      "name": "kobject_create_and_add",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:805",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/mempolicy.c:numa_init_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342344,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585532736,
      "name": "kobject_create_and_add",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:773",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/module/sysfs.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/migrate.c:numa_init_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594203932,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071586686640,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595767760,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:781",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/module/sysfs.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/memory-tiers.c:numa_init_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595767760,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596292160,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:782",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/module/sysfs.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/memory-tiers.c:numa_init_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596292160,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597177072,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:789",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/module/sysfs.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/memory-tiers.c:numa_init_sysfs",
        "mm/huge_memory.c:hugepage_init_sysfs",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:device_add_disk",
        "block/genhd.c:device_add_disk",
        "block/partitions/core.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597177072,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503834816,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:791",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503834816,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236453984,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:791",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236453984,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297683664,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:791",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online",
        "arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init",
        "arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init",
        "arch/powerpc/platforms/powernv/opal-psr.c:opal_psr_init",
        "arch/powerpc/platforms/powernv/opal-sensor-groups.c:opal_sensor_groups_init",
        "arch/powerpc/platforms/powernv/ultravisor.c:__machine_initcall_powernv_uv_init",
        "arch/powerpc/platforms/pseries/mobility.c:__machine_initcall_pseries_mobility_sysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297683664,
      "name": "kobject_create_and_add",
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279726808,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:791",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279726808,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:791",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660952,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071589659904,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:791",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386776,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071589385728,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:791",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104328,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071590103280,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct kobject * kobject_create_and_add(const char * name, struct kobject * parent)
```

```json
{
  "name": "kobject_create_and_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_create_and_add",
      "external": true,
      "loc": "lib/kobject.c:791",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "mm/mm_init.c:mm_sysfs_init",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "fs/namespace.c:mnt_init",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "block/genhd.c:genhd_device_init",
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/partition-generic.c:add_partition",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_init",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/core.c:devices_init",
        "drivers/base/class.c:class_compat_register",
        "drivers/base/firmware.c:firmware_init",
        "drivers/base/module.c:module_add_driver",
        "drivers/base/hypervisor.c:hypervisor_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590154635,
      "name": "kobject_create_and_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071590153584,
      "name": "kobject_create_and_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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

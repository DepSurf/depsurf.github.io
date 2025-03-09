# Function: <code>sysfs_create_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581522080,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:153",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/group.c:sysfs_create_groups"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_add_dev",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:load_module",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/slub.c:sysfs_slab_add",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xen-selfballoon.c:register_xen_selfballooning",
        "drivers/char/tpm/tpm-sysfs.c:tpm_sysfs_add_device",
        "drivers/base/transport_class.c:transport_add_class_device",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/topology.c:topology_cpu_callback",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/misc/bmp085.c:bmp085_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:md_run",
        "drivers/cpufreq/cpufreq_stats.c:__cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522080,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581708294,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:153",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/group.c:sysfs_create_groups"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_add_dev",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:load_module",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/slub.c:sysfs_slab_add",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xen-selfballoon.c:register_xen_selfballooning",
        "drivers/base/transport_class.c:transport_add_class_device",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/topology.c:topology_cpu_callback",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708032,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581796150,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:153",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/group.c:sysfs_create_groups"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:load_module",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/slub.c:sysfs_slab_add",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xen-selfballoon.c:register_xen_selfballooning",
        "drivers/base/transport_class.c:transport_add_class_device",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795888,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581850800,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:153",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:load_module",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xen-selfballoon.c:register_xen_selfballooning",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850800,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582000624,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:153",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:load_module",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/slub.c:sysfs_slab_add",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xen-selfballoon.c:register_xen_selfballooning",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000624,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582188688,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:157",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xen-selfballoon.c:register_xen_selfballooning",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188688,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582283872,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:171",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xen-selfballoon.c:register_xen_selfballooning",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283872,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448736,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:171",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/main.c:pm_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448736,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582547920,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547920,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582854016,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_node",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_add_dev",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:kernel_add_sysfs_param",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:add_sect_attrs",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_register_node",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582854016,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582927072,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_node",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_add_dev",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:kernel_add_sysfs_param",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:add_sect_attrs",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582927072,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582954720,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:add_sect_attrs",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_online",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582954720,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289968,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:add_sect_attrs",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/mempolicy.c:numa_init_sysfs",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289968,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583795824,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:171",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module/sysfs.c:add_sect_attrs",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/migrate.c:numa_init_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583795824,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584415968,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:171",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module/sysfs.c:add_sect_attrs",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "mm/vmscan.c:init_lru_gen",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/memory-tiers.c:numa_init_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/base/transport_class.c:transport_add_class_device",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584415968,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644576,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:175",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module/sysfs.c:add_sect_attrs",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "mm/vmscan.c:init_lru_gen",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/memory-tiers.c:numa_init_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/base/transport_class.c:transport_add_class_device",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644576,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584876960,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:175",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/reboot.c:reboot_ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module/sysfs.c:add_sect_attrs",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "mm/vmscan.c:init_lru_gen",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/memory-tiers.c:numa_init_sysfs",
        "mm/huge_memory.c:hugepage_init_sysfs",
        "mm/huge_memory.c:hugepage_init_sysfs",
        "mm/huge_memory.c:hugepage_init_sysfs",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/acpi_fpdt.c:fpdt_process_subtable",
        "drivers/acpi/acpi_fpdt.c:fpdt_process_subtable",
        "drivers/acpi/acpi_fpdt.c:fpdt_process_subtable",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/base/transport_class.c:transport_add_class_device",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584876960,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494186904,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpuinfo.c:cpuid_cpu_online",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/meson/meson_sm.c:meson_sm_probe",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494186904,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227622756,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227622756,
      "name": "sysfs_create_group",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287876352,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:cpu_add_dev_attr_group",
        "arch/powerpc/platforms/powernv/opal-flash.c:opal_flash_update_init",
        "arch/powerpc/platforms/powernv/opal-dump.c:opal_platform_dump_init",
        "arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init",
        "arch/powerpc/platforms/powernv/opal-sensor-groups.c:opal_sensor_groups_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287876352,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273650464,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_init",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273650464,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582516656,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516656,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582453824,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/hv/vmbus_drv.c:vmbus_add_channel_kobj",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453824,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582507136,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582507136,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sysfs_create_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_create_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588032,
      "name": "sysfs_create_group",
      "external": true,
      "loc": "fs/sysfs/group.c:172",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_setup",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/power/hibernate.c:pm_disk_init",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_sysfs_init",
        "kernel/trace/blktrace.c:blk_trace_init_sysfs",
        "mm/swap_state.c:swap_init_sysfs",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/ksm.c:ksm_init",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/page_idle.c:page_idle_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "block/blk-sysfs.c:blk_register_queue",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/pci/pci-label.c:pci_create_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_expose_list",
        "drivers/acpi/sysfs.c:acpi_irq_stats_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/base/topology.c:topology_add_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588032,
      "name": "sysfs_create_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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

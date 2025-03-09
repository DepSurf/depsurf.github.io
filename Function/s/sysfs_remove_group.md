# Function: <code>sysfs_remove_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522144,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:226",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:free_module",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "fs/sysfs/group.c:sysfs_create_groups",
        "fs/sysfs/group.c:sysfs_remove_groups",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_exit",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/tpm/tpm-sysfs.c:tpm_sysfs_del_device",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_cpu_callback",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/misc/bmp085.c:bmp085_remove",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:__cpufreq_stats_free_table",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522144,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581708096,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:226",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "fs/sysfs/group.c:sysfs_remove_groups",
        "fs/sysfs/group.c:sysfs_create_groups",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_cpu_callback",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708096,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581795952,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:226",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "fs/sysfs/group.c:sysfs_remove_groups",
        "fs/sysfs/group.c:sysfs_create_groups",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795952,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581850864,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:226",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850864,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582000688,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:226",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000688,
      "name": "sysfs_remove_group",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582188752,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:230",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071582188752,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582283936,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:245",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071582283936,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582448800,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:269",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071582448800,
      "name": "sysfs_remove_group",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582547984,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071582547984,
      "name": "sysfs_remove_group",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582852880,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_add_dev",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:kernel_add_sysfs_param",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071582852880,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582925936,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_add_dev",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:kernel_add_sysfs_param",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071582925936,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953584,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_online",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071582953584,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583288832,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071583288832,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583794640,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:269",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/sysfs/group.c:internal_create_groups",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071583794640,
      "name": "sysfs_remove_group",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584414720,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:269",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "mm/hugetlb.c:hugetlb_unregister_node",
        "mm/hugetlb.c:hugetlb_unregister_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/sysfs/group.c:internal_create_groups",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071584414720,
      "name": "sysfs_remove_group",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643280,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:273",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "mm/hugetlb.c:hugetlb_unregister_node",
        "mm/hugetlb.c:hugetlb_unregister_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/sysfs/group.c:internal_create_groups",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071584643280,
      "name": "sysfs_remove_group",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584875664,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:273",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep",
        "kernel/params.c:param_sysfs_builtin",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "mm/hugetlb.c:hugetlb_unregister_node",
        "mm/hugetlb.c:hugetlb_unregister_node",
        "mm/hugetlb.c:hugetlb_sysfs_add_hstate",
        "mm/huge_memory.c:hugepage_exit_sysfs",
        "mm/huge_memory.c:hugepage_exit_sysfs",
        "mm/huge_memory.c:hugepage_init_sysfs",
        "fs/sysfs/group.c:internal_create_groups",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/acpi/acpi_fpdt.c:fpdt_process_subtable",
        "drivers/acpi/acpi_fpdt.c:fpdt_process_subtable",
        "drivers/acpi/acpi_fpdt.c:fpdt_process_subtable",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071584875664,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494187016,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpuinfo.c:cpuid_cpu_offline",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:free_module",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446603336494187016,
      "name": "sysfs_remove_group",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227624216,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:free_module",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_state_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 3227624216,
      "name": "sysfs_remove_group",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287876416,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:cpu_remove_dev_attr_group",
        "arch/powerpc/platforms/powernv/opal-flash.c:opal_flash_update_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287876416,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273650568,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:free_module",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273650568,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582516720,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071582516720,
      "name": "sysfs_remove_group",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582453888,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/hv/vmbus_drv.c:vmbus_remove_channel_attr_group",
        "drivers/devfreq/governor_userspace.c:devfreq_userspace_handler",
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453888,
      "name": "sysfs_remove_group",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582507200,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071582507200,
      "name": "sysfs_remove_group",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void sysfs_remove_group(struct kobject * kobj, const struct attribute_group * grp)
```

```json
{
  "name": "sysfs_remove_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582588096,
      "name": "sysfs_remove_group",
      "external": true,
      "loc": "fs/sysfs/group.c:270",
      "file": "fs/sysfs/group.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:module_param_sysfs_remove",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/trace/blktrace.c:blk_trace_remove_sysfs",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "fs/ecryptfs/main.c:do_sysfs_unregistration",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/pci/pci-label.c:pci_remove_firmware_label_files",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_power_hide_list",
        "drivers/acpi/sysfs.c:interrupt_stats_exit",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/xen/sys-hypervisor.c:hyper_sysfs_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/core.c:devm_attr_group_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/base/transport_class.c:transport_remove_classdev",
        "drivers/base/topology.c:topology_remove_dev",
        "drivers/base/power/sysfs.c:dpm_sysfs_remove",
        "drivers/base/power/sysfs.c:dpm_sysfs_add",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_interface",
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
      "addr": 18446744071582588096,
      "name": "sysfs_remove_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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

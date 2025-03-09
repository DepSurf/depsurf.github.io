# Function: <code>device_remove_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584376048,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:611",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_dh.c:scsi_dh_remove_device",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584376048,
      "name": "device_remove_file",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584713571,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:611",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584711008,
      "name": "device_remove_file",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584904724,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1177",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898352,
      "name": "device_remove_file",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584989884,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1175",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584983888,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585411664,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1310",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585405696,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585653598,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1352",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585648032,
      "name": "device_remove_file",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585783150,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1426",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777456,
      "name": "device_remove_file",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586013531,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1571",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586010432,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586161048,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1608",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586157296,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586919193,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:2086",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "mm/dmapool.c:dma_pool_destroy",
        "block/partitions/core.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914752,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587003382,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:2496",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586998928,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586885894,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:2708",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881360,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587447894,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:2773",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442896,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588765468,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:2798",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/core.c:device_links_driver_bound"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:really_probe",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588763584,
      "name": "device_remove_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588764576,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590256588,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:2996",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/core.c:device_links_driver_bound"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:really_probe",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590253392,
      "name": "device_remove_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071590255184,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590575819,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:3002",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/core.c:device_links_driver_bound"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:really_probe",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590573472,
      "name": "device_remove_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071590574192,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590934219,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:3017",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/core.c:device_links_driver_bound"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_device_destroy",
        "drivers/video/fbdev/core/fbsysfs.c:fb_device_create",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:really_probe",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/thermal/thermal_core.c:thermal_unbind_cdev_from_trip",
        "drivers/thermal/thermal_core.c:thermal_unbind_cdev_from_trip",
        "drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip",
        "drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590931872,
      "name": "device_remove_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071590932592,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498956680,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1608",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/mmc/core/block.c:mmc_blk_remove_req",
        "drivers/mmc/core/block.c:mmc_blk_remove_req",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498951368,
      "name": "device_remove_file",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231527844,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1608",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/sm501.c:sm501_dev_remove",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/mmc/core/block.c:mmc_blk_remove_req",
        "drivers/mmc/core/block.c:mmc_blk_remove_req",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231522648,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292100108,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1608",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:cpu_remove_dev_attr",
        "arch/powerpc/kernel/sysfs.c:unregister_cpu_online",
        "arch/powerpc/kernel/sysfs.c:unregister_cpu_online",
        "arch/powerpc/kernel/sysfs.c:unregister_cpu_online",
        "arch/powerpc/kernel/sysfs.c:unregister_cpu_online",
        "arch/powerpc/kernel/sysfs.c:unregister_cpu_online",
        "arch/powerpc/kernel/sysfs.c:unregister_cpu_online",
        "arch/powerpc/kernel/sysfs.c:unregister_cpu_online",
        "arch/powerpc/kernel/sysfs.c:unregister_cpu_online",
        "arch/powerpc/kernel/sysfs.c:unregister_cpu_online",
        "arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_remove_device",
        "arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_remove_device",
        "arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_remove_device",
        "arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_remove_device",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292093648,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276338686,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1608",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_unregister",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/mmc/core/block.c:mmc_blk_remove_req",
        "drivers/mmc/core/block.c:mmc_blk_remove_req",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276334706,
      "name": "device_remove_file",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585921416,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1608",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585917664,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585770552,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1608",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766800,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586111064,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1608",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107312,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586219672,
      "name": "device_remove_file",
      "external": true,
      "loc": "drivers/base/core.c:1608",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "arch/x86/kernel/cpu/mce/core.c:mce_device_remove",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/compaction.c:compaction_unregister_node",
        "block/partition-generic.c:add_partition",
        "drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/power.c:acpi_power_sysfs_remove",
        "drivers/acpi/battery.c:sysfs_remove_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/dd.c:driver_sysfs_remove",
        "drivers/base/attribute_container.c:attribute_container_remove_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_exit",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/scsi/scsi_sysfs.c:sdev_store_delete",
        "drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215920,
      "name": "device_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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

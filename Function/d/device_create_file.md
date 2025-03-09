# Function: <code>device_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584375904,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:587",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_dh.c:scsi_dh_add_device",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375904,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584710864,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:587",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584710864,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584898208,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1153",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files",
        "drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/bus.c:bus_add_device",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898208,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584983760,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1151",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584983760,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585405568,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1286",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585405568,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585650320,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1328",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585650320,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585779840,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1402",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779840,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586010304,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1547",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586010304,
      "name": "device_create_file",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586157168,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1584",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586157168,
      "name": "device_create_file",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586914624,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:2062",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:tick_init_sysfs",
        "kernel/time/clockevents.c:tick_init_sysfs",
        "kernel/time/clockevents.c:tick_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partitions/core.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914624,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586998800,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:2472",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:tick_init_sysfs",
        "kernel/time/clockevents.c:tick_init_sysfs",
        "kernel/time/clockevents.c:tick_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partitions/core.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586998800,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586881232,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:2684",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partitions/core.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881232,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587442768,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:2749",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partitions/core.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442768,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588759984,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:2774",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partitions/core.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759984,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590248672,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:2972",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partitions/core.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590248672,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590568704,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:2978",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partitions/core.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590568704,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590927104,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:2993",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partitions/core.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_device_create",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip",
        "drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590927104,
      "name": "device_create_file",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498951192,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1584",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/soc/imx/soc-imx8.c:imx8_soc_init",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/arch_topology.c:register_cpu_capacity_sysctl",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498951192,
      "name": "device_create_file",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231522448,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1584",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/id.c:omap_soc_device_init",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/soc/imx/soc-imx8.c:imx8_soc_init",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/arch_topology.c:register_cpu_capacity_sysctl",
        "drivers/mfd/sm501.c:sm501_init_dev",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231522448,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292093408,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1584",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:topology_init",
        "arch/powerpc/kernel/sysfs.c:topology_init",
        "arch/powerpc/kernel/sysfs.c:topology_init",
        "arch/powerpc/kernel/sysfs.c:cpu_add_dev_attr",
        "arch/powerpc/kernel/sysfs.c:register_cpu_online",
        "arch/powerpc/kernel/sysfs.c:register_cpu_online",
        "arch/powerpc/kernel/sysfs.c:register_cpu_online",
        "arch/powerpc/kernel/sysfs.c:register_cpu_online",
        "arch/powerpc/kernel/sysfs.c:register_cpu_online",
        "arch/powerpc/kernel/sysfs.c:register_cpu_online",
        "arch/powerpc/kernel/sysfs.c:register_cpu_online",
        "arch/powerpc/kernel/sysfs.c:register_cpu_online",
        "arch/powerpc/kernel/sysfs.c:register_cpu_online",
        "arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_add_device",
        "arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_add_device",
        "arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_add_device",
        "arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_add_device",
        "arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states",
        "arch/powerpc/platforms/powernv/subcore.c:__machine_initcall_powernv_subcore_init",
        "arch/powerpc/platforms/pseries/suspend.c:__machine_initcall_pseries_pseries_suspend_init",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/attribute_container.c:attribute_container_add_attrs",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292093408,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276334570,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1584",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/base/arch_topology.c:register_cpu_capacity_sysctl",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276334570,
      "name": "device_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585917536,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1584",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585917536,
      "name": "device_create_file",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585766672,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1584",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766672,
      "name": "device_create_file",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586107184,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1584",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107184,
      "name": "device_create_file",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int device_create_file(struct device * dev, const struct device_attribute * attr)
```

```json
{
  "name": "device_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586215792,
      "name": "device_create_file",
      "external": true,
      "loc": "drivers/base/core.c:1584",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/workqueue.c:wq_sysfs_init",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/events/core.c:pmu_dev_alloc",
        "mm/compaction.c:compaction_register_node",
        "mm/dmapool.c:dma_pool_create",
        "block/partition-generic.c:add_partition",
        "drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files",
        "drivers/video/fbdev/core/fbsysfs.c:fb_init_device",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/dd.c:driver_sysfs_add",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev",
        "drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215792,
      "name": "device_create_file",
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

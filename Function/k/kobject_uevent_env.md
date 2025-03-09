# Function: <code>kobject_uevent_env</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582960336,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:164",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:disk_check_events",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject_uevent.c:kobject_uevent",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/virtio_blk.c:virtblk_config_changed_work",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_update_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960336,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1595
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583248000,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:164",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/virtio_blk.c:virtblk_config_changed_work",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_update_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583248000,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1682
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583363312,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:164",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363312,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1682
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588213552,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:305",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213552,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1551
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588763152,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:384",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588763152,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1898
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589141952,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:454",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589141952,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1957
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589376352,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589376352,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1970
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589833536,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589833536,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1976
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590059680,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590059680,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1976
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585056240,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/ata/libata-acpi.c:ata_acpi_dev_uevent",
        "drivers/ata/libata-acpi.c:ata_acpi_ap_uevent",
        "drivers/usb/core/hub.c:port_over_current_notify",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/gov_user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585056240,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1195
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585205712,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:set_capacity_and_notify",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/ata/libata-acpi.c:ata_acpi_dev_uevent",
        "drivers/ata/libata-acpi.c:ata_acpi_ap_uevent",
        "drivers/usb/core/hub.c:port_over_current_notify",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/gov_user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585205712,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1195
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:457",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:set_capacity_and_notify",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/ata/libata-acpi.c:ata_acpi_dev_uevent",
        "drivers/ata/libata-acpi.c:ata_acpi_ap_uevent",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/gov_user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324388,
      "name": "kobject_uevent_env.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585088576,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1276
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:457",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:set_capacity_and_notify",
        "block/disk-events.c:disk_event_uevent",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/ata/libata-acpi.c:ata_acpi_dev_uevent",
        "drivers/ata/libata-acpi.c:ata_acpi_ap_uevent",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/thermal/gov_user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342481,
      "name": "kobject_uevent_env.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585535920,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1366
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586690432,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:457",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:set_capacity_and_notify",
        "block/disk-events.c:disk_event_uevent",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/ata/libata-acpi.c:ata_acpi_dev_uevent",
        "drivers/ata/libata-acpi.c:ata_acpi_ap_uevent",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/hwmon/hwmon.c:hwmon_notify_event",
        "drivers/thermal/gov_user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586690432,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1161
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595771840,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:457",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:set_capacity_and_notify",
        "block/disk-events.c:disk_event_uevent",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/ata/libata-acpi.c:ata_acpi_dev_uevent",
        "drivers/ata/libata-acpi.c:ata_acpi_ap_uevent",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/hwmon/hwmon.c:hwmon_notify_event",
        "drivers/thermal/gov_user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595771840,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1164
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596296400,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:457",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:set_capacity_and_notify",
        "block/disk-events.c:disk_event_uevent",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/ata/libata-acpi.c:ata_acpi_dev_uevent",
        "drivers/ata/libata-acpi.c:ata_acpi_ap_uevent",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/hwmon/hwmon.c:hwmon_notify_event",
        "drivers/thermal/gov_user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596296400,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1166
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597181392,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:457",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:set_capacity_and_notify",
        "block/disk-events.c:disk_event_uevent",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/ata/libata-acpi.c:ata_acpi_dev_uevent",
        "drivers/ata/libata-acpi.c:ata_acpi_ap_uevent",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_property_event",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_hotplug_event",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_hotplug_event",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_lease_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/hwmon/hwmon.c:hwmon_notify_event",
        "drivers/thermal/gov_user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597181392,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1213
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503836776,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503836776,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1904
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236455408,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236455408,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1992
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297687232,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297687232,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2608
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279728850,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279728850,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1710
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589661936,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/nvme/host/core.c:nvme_async_event_work",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589661936,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1976
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589387760,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/nvme/host/core.c:nvme_async_event_work",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589387760,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1976
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590105312,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590105312,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1976
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
int kobject_uevent_env(struct kobject * kobj, enum kobject_action action, char * * envp_ext)
```

```json
{
  "name": "kobject_uevent_env",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590155616,
      "name": "kobject_uevent_env",
      "external": true,
      "loc": "lib/kobject_uevent.c:456",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:set_disk_ro",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/pci/pci-driver.c:pci_uevent_ers",
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/acpi/scan.c:acpi_scan_is_offline",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hcd.c:hcd_died_work",
        "drivers/usb/phy/phy.c:usb_phy_notify_charger_work",
        "drivers/thermal/user_space.c:notify_user_space",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm.c:dm_kobject_uevent",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/extcon/extcon.c:extcon_sync",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject_uevent.c:kobject_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155616,
      "name": "kobject_uevent_env",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1976
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

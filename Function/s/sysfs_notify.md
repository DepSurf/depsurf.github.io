# Function: <code>sysfs_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517024,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:167",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517024,
      "name": "sysfs_notify",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581702960,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:173",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702960,
      "name": "sysfs_notify",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790832,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:173",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790832,
      "name": "sysfs_notify",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845952,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:175",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845952,
      "name": "sysfs_notify",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995712,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:175",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995712,
      "name": "sysfs_notify",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582183312,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:173",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582183312,
      "name": "sysfs_notify",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582278480,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:173",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582278480,
      "name": "sysfs_notify",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582443104,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443104,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582541840,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541840,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582848112,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_over_current_notify",
        "drivers/hwmon/hwmon.c:hwmon_notify_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848112,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582920816,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:173",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_over_current_notify",
        "drivers/hwmon/hwmon.c:hwmon_notify_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582920816,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582948528,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:183",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/hwmon/hwmon.c:hwmon_notify_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948528,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583283760,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:183",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/sysfs.c:ext4_notify_error_sysfs",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/hwmon/hwmon.c:hwmon_notify_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583283760,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583788592,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:180",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/sysfs.c:ext4_notify_error_sysfs",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/hwmon/hwmon.c:hwmon_notify_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788592,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584407952,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:180",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/sysfs.c:ext4_notify_error_sysfs",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/hwmon/hwmon.c:hwmon_notify_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407952,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584636496,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:180",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/sysfs.c:ext4_notify_error_sysfs",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/sysfs.c:usb_update_wireless_status_attr",
        "drivers/hwmon/hwmon.c:hwmon_notify_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584636496,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584868656,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:192",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/sysfs.c:ext4_notify_error_sysfs",
        "drivers/video/backlight/backlight.c:backlight_device_set_brightness",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/sysfs.c:usb_update_wireless_status_attr",
        "drivers/hwmon/hwmon.c:hwmon_notify_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584868656,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494179208,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494179208,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227616312,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/gadget/udc/core.c:usb_gadget_state_work",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227616312,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287865632,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287865632,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273644584,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273644584,
      "name": "sysfs_notify",
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582510576,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582510576,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582447744,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447744,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582501056,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501056,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sysfs_notify(struct kobject * kobj, const char * dir, const char * attr)
```

```json
{
  "name": "sysfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582581664,
      "name": "sysfs_notify",
      "external": true,
      "loc": "fs/sysfs/file.c:172",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:backlight_generate_event",
        "drivers/tty/tty_io.c:console_sysfs_notify",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/usb/core/hub.c:port_event",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581664,
      "name": "sysfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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

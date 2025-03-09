# Function: <code>device_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584379088,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:1850",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_destroy_ndctl",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584379088,
      "name": "device_destroy",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584714064,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:1850",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714064,
      "name": "device_destroy",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584905232,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2441",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584905232,
      "name": "device_destroy",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584990464,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2439",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584990464,
      "name": "device_destroy",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585412416,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2574",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412416,
      "name": "device_destroy",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585654336,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2621",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:__unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585654336,
      "name": "device_destroy",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585783888,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2696",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:__unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585783888,
      "name": "device_destroy",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586014240,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2950",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586014240,
      "name": "device_destroy",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161760,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2980",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161760,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919728,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:3448",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919728,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587004608,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:3860",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004608,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586887120,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:4087",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586887120,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587449424,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:4152",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449424,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588767136,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:4186",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767136,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590258400,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:4405",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:unregister_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590258400,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void device_destroy(const struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590577664,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:4408",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:unregister_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590577664,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void device_destroy(const struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590936064,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:4421",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbsysfs.c:fb_device_destroy",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590936064,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498957432,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2980",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498957432,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231528628,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2980",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/mtd/mtdcore.c:mtd_release",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev",
        "sound/sound_core.c:sound_remove_unit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231528628,
      "name": "device_destroy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292101104,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2980",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292101104,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276339348,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2980",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276339348,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585922128,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2980",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585922128,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585771264,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2980",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771264,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586111776,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2980",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111776,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void device_destroy(struct class * class, dev_t devt)
```

```json
{
  "name": "device_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586220384,
      "name": "device_destroy",
      "external": true,
      "loc": "drivers/base/core.c:2980",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_remove_sysfs",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/pps/pps.c:pps_unregister_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586220384,
      "name": "device_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class * class</code> ➡️ <code>const struct class * class</code>
</li>
</ul>
</details>
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

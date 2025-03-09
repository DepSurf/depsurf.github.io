# Function: <code>device_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584386192,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:1778",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386192,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584721088,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:1778",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721088,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584910880,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2369",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_register_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584910880,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584996160,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2367",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996160,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585418048,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2502",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418048,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585660768,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2549",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660768,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585787040,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2624",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585787040,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586017872,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2878",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586017872,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586165584,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2915",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165584,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586923888,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:3382",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923888,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587015568,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:3794",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015568,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586899200,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:4021",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586899200,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587460896,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:4086",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587460896,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588780032,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:4120",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "mm/backing-dev.c:bdi_register_va",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588780032,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590273792,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:4339",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "mm/backing-dev.c:bdi_register_va",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590273792,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct device * device_create(const struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590594208,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:4345",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "mm/backing-dev.c:bdi_register_va",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590594208,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct device * device_create(const struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590953168,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:4358",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "mm/backing-dev.c:bdi_register_va",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbsysfs.c:fb_device_create",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590953168,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498960896,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2915",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/bus/vexpress-config.c:vexpress_config_bridge_register",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498960896,
      "name": "device_create",
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231531240,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2915",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/bus/vexpress-config.c:vexpress_config_bridge_register",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231531240,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292105936,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2915",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292105936,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276342392,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2915",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276342392,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585925952,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2915",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585925952,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585775088,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2915",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "block/bsg.c:bsg_register_queue",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585775088,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586115600,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2915",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115600,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct device * device_create(struct class * class, struct device * parent, dev_t devt, void * drvdata, const char * fmt, void (anon))
```

```json
{
  "name": "device_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586223728,
      "name": "device_create",
      "external": true,
      "loc": "drivers/base/core.c:2915",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "block/bsg.c:bsg_register_queue",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_export",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/tty/vt/vc_screen.c:vcs_make_sysfs",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586223728,
      "name": "device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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

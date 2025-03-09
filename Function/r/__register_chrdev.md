# Function: <code>__register_chrdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011616,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:242",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011616,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170032,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:246",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170032,
      "name": "__register_chrdev",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247008,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:246",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247008,
      "name": "__register_chrdev",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295056,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:246",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295056,
      "name": "__register_chrdev",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434848,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:271",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434848,
      "name": "__register_chrdev",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592416,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:271",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592416,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678272,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:271",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678272,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796304,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796304,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868928,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868928,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094672,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094672,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141488,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141488,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166272,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166272,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483472,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483472,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583004528,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004528,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566560,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566560,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583782656,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782656,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583988240,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fb_chrdev.c:fb_register_chrdev",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/gpu/drm/drm_drv.c:drm_core_init",
        "drivers/accel/drm_accel.c:accel_core_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583988240,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493341496,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493341496,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226934924,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/mtd/mtdchar.c:init_mtdchar",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init",
        "sound/sound_core.c:init_soundcore",
        "sound/core/sound.c:alsa_sound_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226934924,
      "name": "__register_chrdev",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286886672,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286886672,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273071300,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273071300,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837664,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837664,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775328,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775328,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828976,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828976,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name, const struct file_operations * fops)
```

```json
{
  "name": "__register_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898336,
      "name": "__register_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:268",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898336,
      "name": "__register_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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

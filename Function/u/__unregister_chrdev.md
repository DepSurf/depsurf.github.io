# Function: <code>__unregister_chrdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010768,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:309",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010768,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169136,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:313",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169136,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246112,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:313",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246112,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293504,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:313",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293504,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433168,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:338",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433168,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591216,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:338",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591216,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677968,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:338",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677968,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581795984,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795984,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868592,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868592,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582095312,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095312,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142128,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142128,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166656,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166656,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483856,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483856,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005088,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005088,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583567184,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583567184,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583783280,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583783280,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583988864,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fb_chrdev.c:fb_unregister_chrdev",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/gpu/drm/drm_drv.c:drm_core_init",
        "drivers/accel/drm_accel.c:accel_core_exit",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583988864,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493341072,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493341072,
      "name": "__unregister_chrdev",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226934572,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/mtd/mtdchar.c:cleanup_mtdchar",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup",
        "sound/sound_core.c:sound_remove_unit",
        "sound/sound_core.c:cleanup_soundcore",
        "sound/sound_core.c:init_soundcore",
        "sound/core/sound.c:alsa_sound_exit",
        "sound/core/sound.c:alsa_sound_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226934572,
      "name": "__unregister_chrdev",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286883344,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286883344,
      "name": "__unregister_chrdev",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273070928,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273070928,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837328,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837328,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774992,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774992,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828640,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828640,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "__unregister_chrdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898000,
      "name": "__unregister_chrdev",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_major_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898000,
      "name": "__unregister_chrdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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

# Function: <code>misc_deregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584176912,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:249",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_exit",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_exit",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/lightnvm/core.c:nvm_mod_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176912,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515952,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:249",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/lightnvm/core.c:nvm_mod_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515952,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698064,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:249",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698064,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780192,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:250",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780192,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585200288,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:251",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585200288,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437392,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:238",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437392,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585561040,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:238",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585561040,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781555,
      "name": "misc_deregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585781408,
      "name": "misc_deregister",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585924160,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585924160,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661200,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661200,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586771152,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771152,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586651840,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651840,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587200096,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587200096,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588503424,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:241",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588503424,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589945248,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:259",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modexit",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_exit",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589945248,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590254512,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:273",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modexit",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_exit",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590254512,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590595488,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:273",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modexit",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_exit",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590595488,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498750816,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498750816,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231370720,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231370720,
      "name": "misc_deregister",
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291907664,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/char/nvram.c:nvram_module_exit",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291907664,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276252344,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276252344,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585685136,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585685136,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585545008,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545008,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585874560,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874560,
      "name": "misc_deregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void misc_deregister(struct miscdevice * misc)
```

```json
{
  "name": "misc_deregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982432,
      "name": "misc_deregister",
      "external": true,
      "loc": "drivers/char/misc.c:239",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit",
        "fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:unregister_miscdev",
        "drivers/char/agp/frontend.c:agp_frontend_cleanup",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_exit",
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_psaux_unregister",
        "drivers/input/misc/uinput.c:uinput_misc_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982432,
      "name": "misc_deregister",
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

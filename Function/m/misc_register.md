# Function: <code>misc_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584176528,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:185",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/lightnvm/core.c:nvm_mod_init",
        "drivers/block/loop.c:loop_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/misc/uinput.c:uinput_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176528,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515568,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:185",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:nvm_mod_init",
        "drivers/block/loop.c:loop_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/misc/uinput.c:uinput_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515568,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584697680,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:185",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584697680,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584779808,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:185",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779808,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199904,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:186",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199904,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437024,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437024,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560672,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560672,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585781024,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781024,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585923776,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585923776,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586660816,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:cpu_latency_qos_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586660816,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586770768,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "kernel/power/qos.c:cpu_latency_qos_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586770768,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586651456,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init",
        "kernel/power/qos.c:cpu_latency_qos_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651456,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587199712,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init",
        "kernel/power/qos.c:cpu_latency_qos_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587199712,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588503024,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:175",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_guest_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init",
        "kernel/power/qos.c:cpu_latency_qos_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/pci/vgaarb.c:vga_arb_device_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588503024,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589944784,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:197",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init",
        "kernel/power/qos.c:cpu_latency_qos_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/userfaultfd.c:userfaultfd_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/pci/vgaarb.c:vga_arb_device_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589944784,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590254048,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:211",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init",
        "kernel/power/qos.c:cpu_latency_qos_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/userfaultfd.c:userfaultfd_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/pci/vgaarb.c:vga_arb_device_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590254048,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590595024,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:211",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init",
        "kernel/power/qos.c:cpu_latency_qos_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/userfaultfd.c:userfaultfd_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/pci/vgaarb.c:vga_arb_device_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590595024,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498750304,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498750304,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231370308,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231370308,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291907056,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_power_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/char/nvram.c:nvram_module_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291907056,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276251932,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_power_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276251932,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585684752,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585684752,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585544624,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585544624,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585874176,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874176,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int misc_register(struct miscdevice * misc)
```

```json
{
  "name": "misc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982048,
      "name": "misc_register",
      "external": true,
      "loc": "drivers/char/misc.c:173",
      "file": "drivers/char/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/power/qos.c:pm_qos_power_init",
        "kernel/power/user.c:snapshot_device_init",
        "fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev",
        "fs/fuse/dev.c:fuse_dev_init",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init",
        "drivers/xen/mcelog.c:xen_late_init_mcelog",
        "drivers/char/hpet.c:hpet_init",
        "drivers/char/hw_random/core.c:hwrng_modinit",
        "drivers/char/agp/frontend.c:agp_frontend_initialize",
        "drivers/lightnvm/core.c:_nvm_misc_init",
        "drivers/block/loop.c:loop_init",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/net/tun.c:tun_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/misc/uinput.c:uinput_misc_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/md/dm-ioctl.c:dm_interface_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982048,
      "name": "misc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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

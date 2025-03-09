# Function: <code>cdev_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010720,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:481",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/rtc/rtc-dev.c:rtc_dev_del_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010720,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169088,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:485",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/rtc/rtc-dev.c:rtc_dev_del_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169088,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246064,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:486",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/rtc/rtc-dev.c:rtc_dev_del_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246064,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293456,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:569",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:tty_driver_kref_put",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293456,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433120,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:594",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433120,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591168,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:594",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591168,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677920,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:594",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677920,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581795936,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:591",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795936,
      "name": "cdev_del",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868544,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:591",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868544,
      "name": "cdev_del",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582095145,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:594",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093552,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582141961,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:594",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139808,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582166617,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:594",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164592,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582483817,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:594",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481696,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583005029,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:594",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002880,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583567109,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:601",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564736,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583783205,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:601",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583781152,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583988789,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:601",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986656,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493341008,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:591",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:tty_driver_kref_put",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493341008,
      "name": "cdev_del",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226934512,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:591",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:tty_driver_kref_put",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226934512,
      "name": "cdev_del",
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286883248,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:591",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:tty_driver_kref_put",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286883248,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273070864,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:591",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273070864,
      "name": "cdev_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837280,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:591",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837280,
      "name": "cdev_del",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774944,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:591",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/dax/device.c:dev_dax_probe",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774944,
      "name": "cdev_del",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828592,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:591",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828592,
      "name": "cdev_del",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void cdev_del(struct cdev * p)
```

```json
{
  "name": "cdev_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897952,
      "name": "cdev_del",
      "external": true,
      "loc": "fs/char_dev.c:591",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_del",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__unregister_chrdev",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897952,
      "name": "cdev_del",
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

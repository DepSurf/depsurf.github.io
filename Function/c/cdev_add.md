# Function: <code>cdev_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010624,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:452",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/rtc-dev.c:rtc_dev_add_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010624,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168992,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:456",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/rtc-dev.c:rtc_dev_add_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168992,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581245968,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:457",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/rtc-dev.c:rtc_dev_add_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581245968,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293360,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:457",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293360,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433024,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:482",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433024,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591072,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:482",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591072,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677824,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:482",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677824,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581795840,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795840,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868448,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868448,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093424,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_cdev_add",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093424,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139680,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_cdev_add",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139680,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164464,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_cdev_add",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164464,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481568,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "drivers/tty/tty_io.c:tty_cdev_add",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481568,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002704,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "drivers/tty/tty_io.c:tty_cdev_add",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002704,
      "name": "cdev_add",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583564560,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "drivers/tty/tty_io.c:tty_cdev_add",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564560,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780976,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "drivers/tty/tty_io.c:tty_cdev_add",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780976,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986480,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "drivers/tty/tty_io.c:tty_cdev_add",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986480,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493340888,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493340888,
      "name": "cdev_add",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226934320,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_cdev_add",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226934320,
      "name": "cdev_add",
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286883104,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286883104,
      "name": "cdev_add",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273070752,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273070752,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837184,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837184,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774848,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/dax/device.c:dev_dax_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774848,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828496,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828496,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int cdev_add(struct cdev * p, dev_t dev, unsigned int count)
```

```json
{
  "name": "cdev_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897856,
      "name": "cdev_add",
      "external": true,
      "loc": "fs/char_dev.c:479",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add",
        "fs/char_dev.c:__register_chrdev",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/virtio_console.c:add_port",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/pps/pps.c:pps_register_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897856,
      "name": "cdev_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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

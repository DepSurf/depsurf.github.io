# Function: <code>cdev_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010816,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:538",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/rtc-dev.c:rtc_dev_prepare",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010816,
      "name": "cdev_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169184,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:542",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/rtc-dev.c:rtc_dev_prepare",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169184,
      "name": "cdev_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246160,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:543",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/rtc-dev.c:rtc_dev_prepare",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246160,
      "name": "cdev_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293616,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:626",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/rtc-dev.c:rtc_dev_prepare",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293616,
      "name": "cdev_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433280,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:651",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/rtc-dev.c:rtc_dev_prepare",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433280,
      "name": "cdev_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591440,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:651",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/rtc-dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591440,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678496,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:651",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678496,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796528,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:648",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796528,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581869152,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:648",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581869152,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093600,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:651",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093600,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139856,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:651",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139856,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164640,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:651",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164640,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481744,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:651",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_register_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481744,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002944,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:651",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_register_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002944,
      "name": "cdev_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583564816,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:658",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_register_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564816,
      "name": "cdev_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583781232,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:658",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583781232,
      "name": "cdev_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986736,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:658",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986736,
      "name": "cdev_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493341784,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:648",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493341784,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226935116,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:648",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226935116,
      "name": "cdev_init",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286883760,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:648",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286883760,
      "name": "cdev_init",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273071526,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:648",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273071526,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837888,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:648",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837888,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775552,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:648",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/dax/device.c:dev_dax_probe",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775552,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829200,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:648",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829200,
      "name": "cdev_init",
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
void cdev_init(struct cdev * cdev, const struct file_operations * fops)
```

```json
{
  "name": "cdev_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898560,
      "name": "cdev_init",
      "external": true,
      "loc": "fs/char_dev.c:648",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/dev.c:rtc_dev_prepare",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898560,
      "name": "cdev_init",
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

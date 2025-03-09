# Function: <code>cdev_device_del</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293552,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:546",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:rtc_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293552,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433216,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:571",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:rtc_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433216,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591376,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:571",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:rtc_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591376,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678128,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:571",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678128,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796160,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:568",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796160,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868784,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:568",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868784,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582095104,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:571",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_disconnect",
        "drivers/input/mousedev.c:mousedev_connect",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095104,
      "name": "cdev_device_del",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141920,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:571",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_disconnect",
        "drivers/input/mousedev.c:mousedev_connect",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_unregister_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141920,
      "name": "cdev_device_del",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166576,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:571",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_disconnect",
        "drivers/input/mousedev.c:mousedev_connect",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_unregister_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166576,
      "name": "cdev_device_del",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483776,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:571",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_disconnect",
        "drivers/input/mousedev.c:mousedev_connect",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_unregister_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483776,
      "name": "cdev_device_del",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583004976,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:571",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_remove",
        "drivers/input/mousedev.c:mousedev_disconnect",
        "drivers/input/mousedev.c:mousedev_connect",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_unregister_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004976,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583567056,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:578",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_remove",
        "drivers/input/mousedev.c:mousedev_exit",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/mousedev.c:mousedev_disconnect",
        "drivers/input/mousedev.c:mousedev_connect",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_unregister_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583567056,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583783152,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:578",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_remove",
        "drivers/input/mousedev.c:mousedev_exit",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/mousedev.c:mousedev_disconnect",
        "drivers/input/mousedev.c:mousedev_connect",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_unregister_device",
        "drivers/i2c/i2c-dev.c:i2cdev_detach_adapter",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583783152,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583988736,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:578",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_remove",
        "drivers/input/mousedev.c:mousedev_exit",
        "drivers/input/mousedev.c:mousedev_init",
        "drivers/input/mousedev.c:mousedev_disconnect",
        "drivers/input/mousedev.c:mousedev_connect",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_unregister_device",
        "drivers/i2c/i2c-dev.c:i2cdev_detach_adapter",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583988736,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493341320,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:568",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493341320,
      "name": "cdev_device_del",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226934780,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:568",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226934780,
      "name": "cdev_device_del",
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286883632,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:568",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286883632,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273071138,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:568",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273071138,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837520,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:568",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/nvme/host/core.c:nvme_do_delete_ctrl",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837520,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775184,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:568",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/nvme/host/core.c:nvme_do_delete_ctrl",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775184,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828832,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:568",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828832,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void cdev_device_del(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898192,
      "name": "cdev_device_del",
      "external": true,
      "loc": "fs/char_dev.c:568",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_unregister",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/input/mousedev.c:mousedev_destroy",
        "drivers/input/evdev.c:evdev_disconnect",
        "drivers/rtc/class.c:devm_rtc_release_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898192,
      "name": "cdev_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void cdev_device_del(struct cdev * cdev, struct device * dev)
```
</details>
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

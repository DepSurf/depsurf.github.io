# Function: <code>cdev_device_add</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581293712,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:512",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:__rtc_register_device",
        "drivers/rtc/class.c:rtc_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293712,
      "name": "cdev_device_add",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581433376,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:537",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:__rtc_register_device",
        "drivers/rtc/class.c:rtc_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433376,
      "name": "cdev_device_add",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591264,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:537",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:__rtc_register_device",
        "drivers/rtc/class.c:rtc_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591264,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678016,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:537",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:__rtc_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678016,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796048,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:534",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796048,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868656,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:534",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868656,
      "name": "cdev_device_add",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582095392,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:537",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/char/tpm/tpm-chip.c:tpm_add_char_device",
        "drivers/char/tpm/tpm-chip.c:tpm_add_char_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095392,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142208,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:537",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/char/tpm/tpm-chip.c:tpm_add_char_device",
        "drivers/char/tpm/tpm-chip.c:tpm_add_char_device",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142208,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166736,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:537",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166736,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483936,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:537",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_register_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483936,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005184,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:537",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_register_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005184,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583567888,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:544",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "block/bsg.c:bsg_register_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583567888,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583784000,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:544",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583784000,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583989584,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:544",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_register_queue",
        "drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register",
        "drivers/char/tpm/tpm2-space.c:tpm_devs_add",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/i2c/i2c-dev.c:i2cdev_attach_adapter",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583989584,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493341168,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:534",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493341168,
      "name": "cdev_device_add",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226934632,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:534",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226934632,
      "name": "cdev_device_add",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286883440,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:534",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286883440,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273071012,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:534",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273071012,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837392,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:534",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837392,
      "name": "cdev_device_add",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775056,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:534",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775056,
      "name": "cdev_device_add",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828704,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:534",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828704,
      "name": "cdev_device_add",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int cdev_device_add(struct cdev * cdev, struct device * dev)
```

```json
{
  "name": "cdev_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898064,
      "name": "cdev_device_add",
      "external": true,
      "loc": "fs/char_dev.c:534",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:posix_clock_register",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/mousedev.c:mousedev_create",
        "drivers/input/evdev.c:evdev_connect",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898064,
      "name": "cdev_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int cdev_device_add(struct cdev * cdev, struct device * dev)
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

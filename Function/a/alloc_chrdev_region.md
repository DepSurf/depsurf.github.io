# Function: <code>alloc_chrdev_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011488,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:210",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/rtc/rtc-dev.c:rtc_dev_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011488,
      "name": "alloc_chrdev_region",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169984,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:214",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/rtc/rtc-dev.c:rtc_dev_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169984,
      "name": "alloc_chrdev_region",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246960,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:214",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/rtc/rtc-dev.c:rtc_dev_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246960,
      "name": "alloc_chrdev_region",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295008,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:214",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/rtc/rtc-dev.c:rtc_dev_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295008,
      "name": "alloc_chrdev_region",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434800,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:239",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/rtc/rtc-dev.c:rtc_dev_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434800,
      "name": "alloc_chrdev_region",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592368,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:239",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_init",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_fs_init",
        "drivers/rtc/rtc-dev.c:rtc_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592368,
      "name": "alloc_chrdev_region",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677632,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:239",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_init",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_fs_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677632,
      "name": "alloc_chrdev_region",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581795648,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795648,
      "name": "alloc_chrdev_region",
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868256,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868256,
      "name": "alloc_chrdev_region",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094544,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094544,
      "name": "alloc_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141360,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141360,
      "name": "alloc_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166224,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166224,
      "name": "alloc_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483424,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483424,
      "name": "alloc_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583004464,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004464,
      "name": "alloc_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566480,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566480,
      "name": "alloc_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583782576,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782576,
      "name": "alloc_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583988160,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583988160,
      "name": "alloc_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493340528,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493340528,
      "name": "alloc_chrdev_region",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226934028,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226934028,
      "name": "alloc_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286886528,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286886528,
      "name": "alloc_chrdev_region",
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273070416,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273070416,
      "name": "alloc_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836992,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836992,
      "name": "alloc_chrdev_region",
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774656,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774656,
      "name": "alloc_chrdev_region",
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828304,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828304,
      "name": "alloc_chrdev_region",
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
int alloc_chrdev_region(dev_t * dev, unsigned int baseminor, unsigned int count, const char * name)
```

```json
{
  "name": "alloc_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897584,
      "name": "alloc_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:236",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib.c:gpiolib_dev_init",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/dev.c:rtc_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897584,
      "name": "alloc_chrdev_region",
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

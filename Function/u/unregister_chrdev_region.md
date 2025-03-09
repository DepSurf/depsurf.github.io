# Function: <code>unregister_chrdev_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010352,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:285",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/rtc-dev.c:rtc_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010352,
      "name": "unregister_chrdev_region",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168704,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:289",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/rtc-dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168704,
      "name": "unregister_chrdev_region",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581245680,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:289",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/rtc-dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581245680,
      "name": "unregister_chrdev_region",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293040,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:289",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/rtc-dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293040,
      "name": "unregister_chrdev_region",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432704,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:314",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/rtc-dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432704,
      "name": "unregister_chrdev_region",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581590848,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:314",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_init",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/rtc-dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581590848,
      "name": "unregister_chrdev_region",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676832,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:314",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_init",
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676832,
      "name": "unregister_chrdev_region",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794688,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794688,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581867312,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867312,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093312,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093312,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139568,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139568,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164352,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164352,
      "name": "unregister_chrdev_region",
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481456,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481456,
      "name": "unregister_chrdev_region",
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002416,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002416,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583564224,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564224,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780640,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780640,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986144,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986144,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493339528,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/mmc/core/block.c:mmc_blk_exit",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493339528,
      "name": "unregister_chrdev_region",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226933044,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/mmc/core/block.c:mmc_blk_exit",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226933044,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286882608,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286882608,
      "name": "unregister_chrdev_region",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273069498,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/mmc/core/block.c:mmc_blk_exit",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273069498,
      "name": "unregister_chrdev_region",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836048,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836048,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773712,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773712,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827360,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827360,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void unregister_chrdev_region(dev_t from, unsigned int count)
```

```json
{
  "name": "unregister_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896640,
      "name": "unregister_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:311",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/tty/tty_io.c:tty_unregister_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/devio.c:usb_devio_cleanup",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_exit",
        "drivers/rtc/dev.c:rtc_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/media/cec/cec-core.c:cec_devnode_exit",
        "drivers/media/cec/cec-core.c:cec_devnode_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896640,
      "name": "unregister_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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

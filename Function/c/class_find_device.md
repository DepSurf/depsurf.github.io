# Function: <code>class_find_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584403904,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:412",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584403904,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584739248,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:412",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739248,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584929136,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:427",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584929136,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585013872,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:394",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585013872,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585436128,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:394",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436128,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585679264,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:392",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679264,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585809504,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:392",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585809504,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586042736,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:398",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042736,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586190368,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:398",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190368,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586952160,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:399",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:backlight_device_get_by_name",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/net/phy/mdio_bus.c:mdio_find_bus",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952160,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587037136,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:399",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:backlight_device_get_by_name",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/net/phy/mdio_bus.c:mdio_find_bus",
        "drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037136,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586920928,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:399",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:backlight_device_get_by_name",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/net/phy/mdio_bus.c:mdio_find_bus",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_open",
        "drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920928,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587483328,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:399",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:backlight_device_get_by_name",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/net/phy/mdio_bus.c:mdio_find_bus",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_open",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/ptp/ptp_vclock.c:ptp_convert_timestamp",
        "drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587483328,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588805232,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:399",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:backlight_device_get_by_name",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/net/phy/mdio_bus.c:mdio_find_bus",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_open",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/net/wwan/wwan_core.c:wwan_put_debugfs_dir",
        "drivers/net/wwan/wwan_core.c:wwan_get_debugfs_dir",
        "drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588805232,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590302592,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:404",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:backlight_device_get_by_name",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/net/phy/mdio_bus.c:mdio_find_bus",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_open",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/net/wwan/wwan_core.c:wwan_put_debugfs_dir",
        "drivers/net/wwan/wwan_core.c:wwan_get_debugfs_dir",
        "drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590302592,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
struct device * class_find_device(const struct class * class, const struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590623152,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:436",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/early-lookup.c:devt_from_partuuid",
        "block/early-lookup.c:early_lookup_bdev",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:backlight_device_get_by_name",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/net/phy/mdio_bus.c:mdio_find_bus",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_open",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/net/wwan/wwan_core.c:wwan_put_debugfs_dir",
        "drivers/net/wwan/wwan_core.c:wwan_get_debugfs_dir",
        "drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590623152,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
struct device * class_find_device(const struct class * class, const struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590982400,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:435",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/early-lookup.c:devt_from_partuuid",
        "block/early-lookup.c:early_lookup_bdev",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:backlight_device_get_by_name",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/net/phy/mdio_bus.c:mdio_find_bus",
        "drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590982400,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498990264,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:398",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/bus/vexpress-config.c:vexpress_config_init",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:of_find_backlight",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/regulator/of_regulator.c:of_parse_coupled_regulator",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/net/phy/mdio_bus.c:of_mdio_find_bus",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/core/net-sysfs.c:of_find_net_device_by_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498990264,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231558452,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:398",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/bus/vexpress-config.c:vexpress_config_init",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:of_find_backlight",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/regulator/of_regulator.c:of_parse_coupled_regulator",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/net/phy/mdio_bus.c:of_mdio_find_bus",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/core/net-sysfs.c:of_find_net_device_by_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231558452,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292143600,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:398",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/video/backlight/backlight.c:of_find_backlight",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/regulator/of_regulator.c:of_parse_coupled_regulator",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/net/phy/mdio_bus.c:of_mdio_find_bus",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/core/net-sysfs.c:of_find_net_device_by_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292143600,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276365016,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:398",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/regulator/of_regulator.c:of_parse_coupled_regulator",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/net/phy/mdio_bus.c:of_mdio_find_bus",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/core/net-sysfs.c:of_find_net_device_by_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276365016,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585950736,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:398",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950736,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585799792,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:398",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585799792,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586140384,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:398",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586140384,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct device * class_find_device(struct class * class, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "class_find_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586249072,
      "name": "class_find_device",
      "external": true,
      "loc": "drivers/base/class.c:398",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_unexport",
        "drivers/pwm/sysfs.c:pwmchip_sysfs_unexport",
        "drivers/regulator/core.c:regulator_dev_lookup",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/base/core.c:device_destroy",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/hosts.c:scsi_host_lookup",
        "drivers/spi/spi.c:spi_busnum_to_master",
        "drivers/rtc/interface.c:rtc_class_open",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586249072,
      "name": "class_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class * class</code> ➡️ <code>const struct class * class</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device * start</code> ➡️ <code>const struct device * start</code>
</li>
</ul>
</details>
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

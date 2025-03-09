# Function: <code>device_create_with_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584386304,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:1818",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386304,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584721200,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:1818",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/leds/led-class.c:led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721200,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584910992,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2409",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/leds/led-class.c:led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584910992,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584996256,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2407",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996256,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585418144,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2542",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418144,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585660864,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2589",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660864,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585787136,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2664",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585787136,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586017968,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2918",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586017968,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586165680,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2955",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165680,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586923984,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:3423",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923984,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587015664,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:3835",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015664,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586899296,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:4062",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586899296,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587460992,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:4127",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587460992,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588780160,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:4161",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588780160,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590273936,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:4380",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590273936,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * device_create_with_groups(const struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590594352,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:4383",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590594352,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * device_create_with_groups(const struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590953312,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:4396",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590953312,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498961088,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2955",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498961088,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231531352,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2955",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231531352,
      "name": "device_create_with_groups",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292106016,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2955",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292106016,
      "name": "device_create_with_groups",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276342486,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2955",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276342486,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585926048,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2955",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585926048,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585775184,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2955",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585775184,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586115696,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2955",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115696,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct device * device_create_with_groups(struct class * class, struct device * parent, dev_t devt, void * drvdata, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "device_create_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586223824,
      "name": "device_create_with_groups",
      "external": true,
      "loc": "drivers/base/core.c:2955",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register",
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/char/misc.c:misc_register",
        "drivers/char/misc.c:misc_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586223824,
      "name": "device_create_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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

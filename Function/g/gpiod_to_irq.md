# Function: <code>gpiod_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583187408,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1597",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/usb/phy/phy-generic.c:usb_phy_generic_probe",
        "drivers/usb/phy/phy-generic.c:usb_phy_generic_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583187408,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583489264,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2553",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489264,
      "name": "gpiod_to_irq",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583628208,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2743",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628208,
      "name": "gpiod_to_irq",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583667424,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2740",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667424,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922144,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3011",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922144,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584113888,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3203",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113888,
      "name": "gpiod_to_irq",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197008,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3396",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197008,
      "name": "gpiod_to_irq",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387120,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3485",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387120,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584522416,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3839",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522416,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585188384,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4245",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585188384,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585347760,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3069",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585347760,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585232288,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3046",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232288,
      "name": "gpiod_to_irq",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585687568,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3095",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687568,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586852880,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3216",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852880,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587996784,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3286",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996784,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271472,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3327",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271472,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563712,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3520",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563712,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496700056,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3839",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496700056,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229996100,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3839",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/usb/phy/phy-generic.c:usb_phy_generic_probe",
        "drivers/usb/phy/phy-generic.c:usb_phy_generic_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe",
        "sound/soc/soc-jack.c:snd_soc_jack_add_gpios",
        "sound/soc/soc-jack.c:snd_soc_jack_add_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229996100,
      "name": "gpiod_to_irq",
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290788240,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3839",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290788240,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275465588,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3839",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275465588,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584479344,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3839",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479344,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584417472,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3839",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417472,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584474080,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3839",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584474080,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int gpiod_to_irq(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584580208,
      "name": "gpiod_to_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3839",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:gpio_is_visible",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584580208,
      "name": "gpiod_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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

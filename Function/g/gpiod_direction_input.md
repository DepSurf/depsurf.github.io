# Function: <code>gpiod_direction_input</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583194304,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1100",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:_gpiod_direction_output_raw",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194304,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583497872,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2055",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:_gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583497872,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583638016,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2242",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:_gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583638016,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583677600,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2243",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:_gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677600,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583926976,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2385",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926976,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2499",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136631,
      "name": "gpiod_direction_input.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584119008,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2537",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584222263,
      "name": "gpiod_direction_input.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071584204800,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2626",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411300,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071584393872,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2958",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584547863,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071584528768,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_set_config",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219680,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071585197616,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2209",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386324,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071585355440,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2186",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591328726,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071585241216,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2215",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592351584,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071585696928,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2276",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_set_config",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594213348,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071586863808,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588009936,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2346",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_set_config",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588009936,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588284672,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2387",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_set_config",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588284672,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588577632,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2581",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_set_config",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588577632,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496712968,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2958",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496712968,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230004608,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2958",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230004608,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290800256,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2958",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290800256,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275473336,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2958",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275473336,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2958",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504791,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071584485696,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2958",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442919,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071584423824,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2958",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499527,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071584480432,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_input(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_direction_input",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_input",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2958",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:direction_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584605799,
      "name": "gpiod_direction_input.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071584586512,
      "name": "gpiod_direction_input",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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

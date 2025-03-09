# Function: <code>gpiod_direction_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583195200,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1198",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler",
        "drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195200,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583499104,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2169",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583499104,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583639248,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2357",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583639248,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583678752,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2359",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678752,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583930624,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2469",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930624,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136879,
      "name": "gpiod_direction_output.cold.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584124416,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2662",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584222670,
      "name": "gpiod_direction_output.cold.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584209728,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2750",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411934,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071584398416,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3082",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548474,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071584534064,
      "name": "gpiod_direction_output",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3485",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_set_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221638,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071585206704,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2328",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386849,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071585360080,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2305",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591329159,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071585243648,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2334",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592352017,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071585699312,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2395",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_set_config",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594213766,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071586865808,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588012768,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2465",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_set_config",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588012768,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588287376,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_set_config",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588287376,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588580496,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2700",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_set_config",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588580496,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496719032,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3082",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496719032,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230010140,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3082",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230010140,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290807744,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3082",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290807744,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275478168,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3082",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275478168,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3082",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505402,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071584490992,
      "name": "gpiod_direction_output",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3082",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584443530,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071584429120,
      "name": "gpiod_direction_output",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3082",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584500138,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071584485728,
      "name": "gpiod_direction_output",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_output(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3082",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606410,
      "name": "gpiod_direction_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071584591952,
      "name": "gpiod_direction_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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

# Function: <code>gpiod_configure_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583195280,
      "name": "gpiod_configure_flags",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2093",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_hog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195280,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583499264,
      "name": "gpiod_configure_flags",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3094",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_hog",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583499264,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583639424,
      "name": "gpiod_configure_flags",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3215",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_hog",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583639424,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583685680,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3224",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_hog",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583685680,
      "name": "gpiod_configure_flags",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942400,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3557",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_hog",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942400,
      "name": "gpiod_configure_flags",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3775",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_hog",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136932,
      "name": "gpiod_configure_flags.cold.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584131840,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4035",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_hog",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584222740,
      "name": "gpiod_configure_flags.cold.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584216480,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4123",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412101,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071584405296,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4457",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548546,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071584540976,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4930",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221805,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071585213984,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3754",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591388467,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585365216,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3736",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591330777,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585248912,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3795",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592353926,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585704864,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3923",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594216088,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071586873040,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588021568,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4070",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588021568,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588295952,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295952,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588589808,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4307",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588589808,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496727528,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4457",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496727528,
      "name": "gpiod_configure_flags",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230017804,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4457",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230017804,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290817904,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4457",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290817904,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275484178,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4457",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275484178,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4457",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505474,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071584497904,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4457",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584443602,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071584436032,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4457",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584500210,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071584492640,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int gpiod_configure_flags(struct gpio_desc * desc, const char * con_id, long unsigned int lflags, enum gpiod_flags dflags)
```

```json
{
  "name": "gpiod_configure_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_configure_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4457",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606482,
      "name": "gpiod_configure_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071584598912,
      "name": "gpiod_configure_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int lflags</code>
</li>
<li>
<b>Param reordered. </b>
<code>desc, con_id, dflags</code> ➡️ <code>desc, con_id, lflags, dflags</code>
</li>
</ul>
</details>
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

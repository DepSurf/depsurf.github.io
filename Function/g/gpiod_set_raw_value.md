# Function: <code>gpiod_set_raw_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583196368,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1500",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/i2c/i2c-core.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196368,
      "name": "gpiod_set_raw_value",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583497488,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2459",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/i2c/i2c-core.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583497488,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583637632,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2649",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/i2c/i2c-core.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583637632,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583677008,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2646",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677008,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583932208,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2899",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932208,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123136,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3091",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123136,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207888,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3256",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207888,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3344",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411752,
      "name": "gpiod_set_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584396848,
      "name": "gpiod_set_raw_value",
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532192,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3698",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532192,
      "name": "gpiod_set_raw_value",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4104",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221437,
      "name": "gpiod_set_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585204976,
      "name": "gpiod_set_raw_value",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2928",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591388070,
      "name": "gpiod_set_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585361648,
      "name": "gpiod_set_raw_value",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2905",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591330380,
      "name": "gpiod_set_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585245200,
      "name": "gpiod_set_raw_value",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592353305,
      "name": "gpiod_set_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071585700912,
      "name": "gpiod_set_raw_value",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3075",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594214931,
      "name": "gpiod_set_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071586868032,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3145",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596205508,
      "name": "gpiod_set_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588015552,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3186",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596730566,
      "name": "gpiod_set_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588290624,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3379",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597638937,
      "name": "gpiod_set_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588584048,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496708304,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3698",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496708304,
      "name": "gpiod_set_raw_value",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230007820,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3698",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init",
        "drivers/tty/serial/omap-serial.c:serial_omap_config_rs485",
        "drivers/tty/serial/omap-serial.c:serial_omap_start_tx",
        "drivers/tty/serial/omap-serial.c:serial_omap_stop_tx",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230007820,
      "name": "gpiod_set_raw_value",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290804560,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3698",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290804560,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275476324,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3698",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275476324,
      "name": "gpiod_set_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584489120,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3698",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489120,
      "name": "gpiod_set_raw_value",
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584427248,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3698",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584427248,
      "name": "gpiod_set_raw_value",
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584483856,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3698",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584483856,
      "name": "gpiod_set_raw_value",
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
void gpiod_set_raw_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584590000,
      "name": "gpiod_set_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3698",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590000,
      "name": "gpiod_set_raw_value",
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

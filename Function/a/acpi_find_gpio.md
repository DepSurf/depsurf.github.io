# Function: <code>acpi_find_gpio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpio_lookup_flags * flags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583198933,
      "name": "acpi_find_gpio",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1850",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583206336,
      "name": "acpi_find_gpio",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:397",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583206336,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags flags, enum gpio_lookup_flags * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583505221,
      "name": "acpi_find_gpio",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2855",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583514432,
      "name": "acpi_find_gpio",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:398",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583514432,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags flags, enum gpio_lookup_flags * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583656800,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:552",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583656800,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, enum gpio_lookup_flags * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583696768,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:657",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696768,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, enum gpio_lookup_flags * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953296,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:596",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953296,
      "name": "acpi_find_gpio",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, enum gpio_lookup_flags * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584146816,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:655",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146816,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, enum gpio_lookup_flags * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584234448,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:685",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584234448,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584424256,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:732",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424256,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584561024,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:812",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584561024,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585234592,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:819",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585234592,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585392832,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:853",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585392832,
      "name": "acpi_find_gpio",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585276624,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:853",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585276624,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:907",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592355805,
      "name": "acpi_find_gpio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071585733200,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:892",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594217916,
      "name": "acpi_find_gpio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586910064,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
struct gpio_desc * acpi_find_gpio(struct fwnode_handle * fwnode, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:972",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596206426,
      "name": "acpi_find_gpio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588063904,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
struct gpio_desc * acpi_find_gpio(struct fwnode_handle * fwnode, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:974",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596731468,
      "name": "acpi_find_gpio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588338608,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
struct gpio_desc * acpi_find_gpio(struct fwnode_handle * fwnode, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:951",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597639816,
      "name": "acpi_find_gpio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588632848,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496756528,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:812",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496756528,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584517952,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:812",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584517952,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456080,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:812",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456080,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584512688,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:812",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512688,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```

```json
{
  "name": "acpi_find_gpio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618960,
      "name": "acpi_find_gpio",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:812",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618960,
      "name": "acpi_find_gpio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
<code>enum gpio_lookup_flags * lookupflags</code>
</li>
<li>
<b>Param type changed. </b>
<code>enum gpio_lookup_flags * flags</code> ➡️ <code>enum gpiod_flags flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum gpiod_flags * dflags</code>
</li>
<li>
<b>Param removed. </b>
<code>enum gpiod_flags flags</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum gpio_lookup_flags * lookupflags</code> ➡️ <code>long unsigned int * lookupflags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fwnode_handle * fwnode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dev</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct gpio_desc * acpi_find_gpio(struct device * dev, const char * con_id, unsigned int idx, enum gpiod_flags * dflags, long unsigned int * lookupflags)
```
</details>
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

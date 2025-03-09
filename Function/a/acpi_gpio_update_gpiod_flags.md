# Function: <code>acpi_gpio_update_gpiod_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, enum gpiod_flags update)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583697046,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:465",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695040,
      "name": "acpi_gpio_update_gpiod_flags.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583696736,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, enum gpiod_flags update)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583953568,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:404",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951680,
      "name": "acpi_gpio_update_gpiod_flags.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583953264,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584146640,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:471",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146640,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584234272,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:498",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584234272,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:517",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426892,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584424048,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:587",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563580,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584560816,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:594",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236708,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585234384,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:622",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591389637,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585392208,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:622",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591332037,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585276000,
      "name": "acpi_gpio_update_gpiod_flags",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:676",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592355759,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585732480,
      "name": "acpi_gpio_update_gpiod_flags",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:661",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594217861,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071586909232,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588060448,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:697",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588060448,
      "name": "acpi_gpio_update_gpiod_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588335040,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:702",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588335040,
      "name": "acpi_gpio_update_gpiod_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588629184,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:678",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588629184,
      "name": "acpi_gpio_update_gpiod_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496756200,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:587",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496756200,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.h:66",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.h:66",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.h:66",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:587",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520508,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584517744,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:587",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584458636,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584455872,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:587",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515244,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584512480,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_gpio_update_gpiod_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_update_gpiod_flags",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:587",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621516,
      "name": "acpi_gpio_update_gpiod_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584618752,
      "name": "acpi_gpio_update_gpiod_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, enum gpiod_flags update)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_gpio_info * info</code>
</li>
<li>
<b>Param removed. </b>
<code>enum gpiod_flags update</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```
</details>
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags * flags, struct acpi_gpio_info * info)
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

# Function: <code>gpiod_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583198208,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:942",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583198208,
      "name": "gpiod_request",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583502160,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1899",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583502160,
      "name": "gpiod_request",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583641792,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2086",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641792,
      "name": "gpiod_request",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583681136,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2087",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681136,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583936624,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2224",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936624,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584125760,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2338",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125760,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584210128,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2366",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210128,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584398848,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2430",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398848,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584534384,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2762",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534384,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585216346,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3129",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585203584,
      "name": "gpiod_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071585221710,
      "name": "gpiod_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071585210384,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585367610,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1933",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585359872,
      "name": "gpiod_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071591388372,
      "name": "gpiod_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071585361984,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585251695,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1910",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242704,
      "name": "gpiod_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071591330682,
      "name": "gpiod_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071585245536,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585707663,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1932",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585698096,
      "name": "gpiod_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071592353649,
      "name": "gpiod_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071585701280,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586875942,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1993",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586866512,
      "name": "gpiod_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071594215788,
      "name": "gpiod_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071586868768,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588016560,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2063",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588016560,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588291280,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2102",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291280,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588584976,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2285",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588584976,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496719480,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2762",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496719480,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230010552,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2762",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230010552,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290809280,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2762",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290809280,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275478488,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2762",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275478488,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584491312,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2762",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584491312,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584429440,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2762",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584429440,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584486048,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2762",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486048,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int gpiod_request(struct gpio_desc * desc, const char * label)
```

```json
{
  "name": "gpiod_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584592272,
      "name": "gpiod_request",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2762",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592272,
      "name": "gpiod_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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

# Function: <code>acpi_get_gpiod_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct gpio_desc * acpi_get_gpiod_by_index(struct acpi_device * adev, const char * propname, int index, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583208048,
      "name": "acpi_get_gpiod_by_index",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:510",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583208048,
      "name": "acpi_get_gpiod_by_index",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct gpio_desc * acpi_get_gpiod_by_index(struct acpi_device * adev, const char * propname, int index, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583516192,
      "name": "acpi_get_gpiod_by_index",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:516",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583516192,
      "name": "acpi_get_gpiod_by_index",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct gpio_desc * acpi_get_gpiod_by_index(struct acpi_device * adev, const char * propname, int index, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583654224,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:519",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583654224,
      "name": "acpi_get_gpiod_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583694425,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:624",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694032,
      "name": "acpi_get_gpiod_by_index.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583951097,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:563",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950704,
      "name": "acpi_get_gpiod_by_index.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584144348,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:622",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143984,
      "name": "acpi_get_gpiod_by_index.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584233692,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:652",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233328,
      "name": "acpi_get_gpiod_by_index.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584423324,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:699",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422960,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584560156,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:769",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584559792,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585231548,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:776",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585231184,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585392423,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:810",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585389184,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585276215,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:810",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585273392,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585732699,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:864",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585729664,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071592355492,
      "name": "acpi_get_gpiod_by_index.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct gpio_desc * acpi_get_gpiod_by_index(struct acpi_device * adev, const char * propname, int index, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:849",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586905792,
      "name": "acpi_get_gpiod_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071594217529,
      "name": "acpi_get_gpiod_by_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct gpio_desc * acpi_get_gpiod_by_index(struct acpi_device * adev, const char * propname, int index, struct acpi_gpio_info * info)
```

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:890",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588059088,
      "name": "acpi_get_gpiod_by_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071596206215,
      "name": "acpi_get_gpiod_by_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588337959,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:892",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333712,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071596731269,
      "name": "acpi_get_gpiod_by_index.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588632199,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:868",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588627600,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071597639623,
      "name": "acpi_get_gpiod_by_index.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496755480,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:769",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496755048,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584517084,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:769",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584516720,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584455212,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:769",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454848,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584511820,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:769",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511456,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpiod_by_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584618092,
      "name": "acpi_get_gpiod_by_index",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:769",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617728,
      "name": "acpi_get_gpiod_by_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct gpio_desc * acpi_get_gpiod_by_index(struct acpi_device * adev, const char * propname, int index, struct acpi_gpio_info * info)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct gpio_desc * acpi_get_gpiod_by_index(struct acpi_device * adev, const char * propname, int index, struct acpi_gpio_info * info)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct gpio_desc * acpi_get_gpiod_by_index(struct acpi_device * adev, const char * propname, int index, struct acpi_gpio_info * info)
```
</details>
</li>
</ul>

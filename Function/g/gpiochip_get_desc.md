# Function: <code>gpiochip_get_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583188666,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:94",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583198160,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583505713,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:112",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583502112,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583645465,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:115",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641744,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583686029,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:116",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681088,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583942990,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:131",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936576,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584132357,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:139",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125712,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584217205,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:140",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210080,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584406037,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:140",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398784,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584541717,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534320,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * gc, unsigned int hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585197525,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_find",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186496,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * gc, unsigned int hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585358360,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:139",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_find",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:linereq_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585345888,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * gc, unsigned int hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585249990,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585230400,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * gc, unsigned int hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585705942,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585685696,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * gc, unsigned int hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586860196,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog",
        "drivers/gpio/gpiolib.c:gpio_name_to_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586851232,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * gc, unsigned int hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588003163,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog",
        "drivers/gpio/gpiolib.c:gpio_name_to_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587994720,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * gc, unsigned int hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588278859,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:159",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog",
        "drivers/gpio/gpiolib.c:gpio_name_to_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588269392,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * gc, unsigned int hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588570638,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:138",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_dup_line_label",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog",
        "drivers/gpio/gpiolib.c:gpio_name_to_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588561632,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496728556,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496719392,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230018884,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230010500,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290819876,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290809216,
      "name": "gpiochip_get_desc",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275485096,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_machine_hog"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275478428,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584498645,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584491248,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584436773,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584429376,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584493381,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485984,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct gpio_desc * gpiochip_get_desc(struct gpio_chip * chip, u16 hwnum)
```

```json
{
  "name": "gpiochip_get_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584599653,
      "name": "gpiochip_get_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592208,
      "name": "gpiochip_get_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip * gc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip * chip</code>
</li>
<li>
<b>Param type changed. </b>
<code>u16 hwnum</code> ➡️ <code>unsigned int hwnum</code>
</li>
</ul>
</details>
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

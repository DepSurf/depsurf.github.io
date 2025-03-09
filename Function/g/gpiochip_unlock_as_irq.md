# Function: <code>gpiochip_unlock_as_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583190576,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1643",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190576,
      "name": "gpiochip_unlock_as_irq.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583190608,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583493186,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2627",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493088,
      "name": "gpiochip_unlock_as_irq.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583493136,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629040,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2829",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629040,
      "name": "gpiochip_unlock_as_irq",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583667872,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2826",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667872,
      "name": "gpiochip_unlock_as_irq",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922592,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3097",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922592,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584116048,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3289",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116048,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584199408,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3484",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199408,
      "name": "gpiochip_unlock_as_irq",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584388256,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3573",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388256,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584524144,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3927",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524144,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void gpiochip_unlock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585195328,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4335",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585195328,
      "name": "gpiochip_unlock_as_irq",
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
void gpiochip_unlock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585353440,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3159",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585353440,
      "name": "gpiochip_unlock_as_irq",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585236912,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3136",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236912,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void gpiochip_unlock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585692240,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3195",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585692240,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void gpiochip_unlock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586855232,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3316",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855232,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void gpiochip_unlock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588000192,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3386",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000192,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void gpiochip_unlock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588274880,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3427",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588274880,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void gpiochip_unlock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588567280,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3620",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588567280,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496709952,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3927",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_relres",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_release_resources",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_release_resources",
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496709952,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229997960,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3927",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_relres",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_release_resources",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_release_resources",
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_irq_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229997960,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290791696,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3927",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290791696,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275467650,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3927",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275467650,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584481072,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3927",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584481072,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584419200,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3927",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584419200,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584475808,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3927",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475808,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void gpiochip_unlock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_unlock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581936,
      "name": "gpiochip_unlock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3927",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_relres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581936,
      "name": "gpiochip_unlock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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

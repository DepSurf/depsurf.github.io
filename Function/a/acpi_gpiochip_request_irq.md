# Function: <code>acpi_gpiochip_request_irq</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584232464,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:153",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232464,
      "name": "acpi_gpiochip_request_irq.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:159",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422080,
      "name": "acpi_gpiochip_request_irq.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584426844,
      "name": "acpi_gpiochip_request_irq.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:171",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558912,
      "name": "acpi_gpiochip_request_irq.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584563551,
      "name": "acpi_gpiochip_request_irq.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void acpi_gpiochip_request_irq(struct acpi_gpio_chip * acpi_gpio, struct acpi_gpio_event * event)
```

```json
{
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:171",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585229600,
      "name": "acpi_gpiochip_request_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071585236462,
      "name": "acpi_gpiochip_request_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void acpi_gpiochip_request_irq(struct acpi_gpio_chip * acpi_gpio, struct acpi_gpio_event * event)
```

```json
{
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:171",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585387600,
      "name": "acpi_gpiochip_request_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071591389390,
      "name": "acpi_gpiochip_request_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585271792,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:171",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585728182,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:222",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586907014,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:219",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:250",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588060688,
      "name": "acpi_gpiochip_request_irq.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071596206284,
      "name": "acpi_gpiochip_request_irq.isra.0.cold",
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
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:252",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588335264,
      "name": "acpi_gpiochip_request_irq.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071596731338,
      "name": "acpi_gpiochip_request_irq.isra.0.cold",
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
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:228",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588629408,
      "name": "acpi_gpiochip_request_irq.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071597639686,
      "name": "acpi_gpiochip_request_irq.isra.0.cold",
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
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496754064,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:171",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496754064,
      "name": "acpi_gpiochip_request_irq.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:171",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515840,
      "name": "acpi_gpiochip_request_irq.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584520479,
      "name": "acpi_gpiochip_request_irq.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:171",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584453968,
      "name": "acpi_gpiochip_request_irq.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584458607,
      "name": "acpi_gpiochip_request_irq.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:171",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584510576,
      "name": "acpi_gpiochip_request_irq.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584515215,
      "name": "acpi_gpiochip_request_irq.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
  "name": "acpi_gpiochip_request_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irq",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:171",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584616848,
      "name": "acpi_gpiochip_request_irq.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584621487,
      "name": "acpi_gpiochip_request_irq.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void acpi_gpiochip_request_irq(struct acpi_gpio_chip * acpi_gpio, struct acpi_gpio_event * event)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void acpi_gpiochip_request_irq(struct acpi_gpio_chip * acpi_gpio, struct acpi_gpio_event * event)
```
</details>
</li>
</ul>

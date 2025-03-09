# Function: <code>acpi_gpiochip_request_irqs</code>

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
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584232998,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:179",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584422630,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:188",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584559462,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:200",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip * acpi_gpio)
```

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585233580,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:200",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236492,
      "name": "acpi_gpiochip_request_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip * acpi_gpio)
```

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585392156,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:200",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591389420,
      "name": "acpi_gpiochip_request_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip * acpi_gpio)
```

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:200",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271728,
      "name": "acpi_gpiochip_request_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071591331865,
      "name": "acpi_gpiochip_request_irqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip * acpi_gpio)
```

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:251",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585728112,
      "name": "acpi_gpiochip_request_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071592355344,
      "name": "acpi_gpiochip_request_irqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip * acpi_gpio)
```

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:247",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586906944,
      "name": "acpi_gpiochip_request_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071594217606,
      "name": "acpi_gpiochip_request_irqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627979670,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:278",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619745462,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:280",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622053622,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:256",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496754680,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:200",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
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
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584516390,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:200",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584454518,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:200",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584511126,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:200",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpiochip_request_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584617398,
      "name": "acpi_gpiochip_request_irqs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:200",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip * acpi_gpio)
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip * acpi_gpio)
```
</details>
</li>
</ul>

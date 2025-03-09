# Function: <code>acpi_gpio_irq_is_wake</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584556615,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:243",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585233096,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:243",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585390956,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:305",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585275055,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:305",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585732063,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:359",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586909021,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:355",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool acpi_gpio_irq_is_wake(struct device * parent, const struct acpi_resource_gpio * agpio)
```

```json
{
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588057600,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:387",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057600,
      "name": "acpi_gpio_irq_is_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
bool acpi_gpio_irq_is_wake(struct device * parent, const struct acpi_resource_gpio * agpio)
```

```json
{
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588332224,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:389",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332224,
      "name": "acpi_gpio_irq_is_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
bool acpi_gpio_irq_is_wake(struct device * parent, const struct acpi_resource_gpio * agpio)
```

```json
{
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588626096,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:365",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626096,
      "name": "acpi_gpio_irq_is_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496751424,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:243",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584513543,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:243",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584451671,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:243",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584508279,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:243",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
  "name": "acpi_gpio_irq_is_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584614551,
      "name": "acpi_gpio_irq_is_wake",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:243",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool acpi_gpio_irq_is_wake(struct device * parent, const struct acpi_resource_gpio * agpio)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

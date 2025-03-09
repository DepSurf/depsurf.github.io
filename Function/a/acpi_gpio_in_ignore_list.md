# Function: <code>acpi_gpio_in_ignore_list</code>

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
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584556637,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:208",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool acpi_gpio_in_ignore_list(const char * controller_in, int pin_in)
```

```json
{
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:208",
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
      "addr": 18446744071585229344,
      "name": "acpi_gpio_in_ignore_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071585236431,
      "name": "acpi_gpio_in_ignore_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
bool acpi_gpio_in_ignore_list(const char * controller_in, int pin_in)
```

```json
{
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:270",
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
      "addr": 18446744071585387344,
      "name": "acpi_gpio_in_ignore_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071591389359,
      "name": "acpi_gpio_in_ignore_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
bool acpi_gpio_in_ignore_list(const char * controller_in, int pin_in)
```

```json
{
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:270",
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
      "addr": 18446744071585271472,
      "name": "acpi_gpio_in_ignore_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071591331834,
      "name": "acpi_gpio_in_ignore_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
bool acpi_gpio_in_ignore_list(const char * controller_in, int pin_in)
```

```json
{
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:324",
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
      "addr": 18446744071585727840,
      "name": "acpi_gpio_in_ignore_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071592355292,
      "name": "acpi_gpio_in_ignore_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
bool acpi_gpio_in_ignore_list(const char * controller_in, unsigned int pin_in)
```

```json
{
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:320",
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
      "addr": 18446744071586904400,
      "name": "acpi_gpio_in_ignore_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071594217430,
      "name": "acpi_gpio_in_ignore_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
bool acpi_gpio_in_ignore_list(const char * ignore_list, const char * controller_in, unsigned int pin_in)
```

```json
{
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:351",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_is_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057264,
      "name": "acpi_gpio_in_ignore_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071596206116,
      "name": "acpi_gpio_in_ignore_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
bool acpi_gpio_in_ignore_list(const char * ignore_list, const char * controller_in, unsigned int pin_in)
```

```json
{
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:353",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_is_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331888,
      "name": "acpi_gpio_in_ignore_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071596731171,
      "name": "acpi_gpio_in_ignore_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
bool acpi_gpio_in_ignore_list(const char * ignore_list, const char * controller_in, unsigned int pin_in)
```

```json
{
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:329",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_is_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588625760,
      "name": "acpi_gpio_in_ignore_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071597639525,
      "name": "acpi_gpio_in_ignore_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496751456,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:208",
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
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584513565,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:208",
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
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584451693,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:208",
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
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584508301,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:208",
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
  "name": "acpi_gpio_in_ignore_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584614573,
      "name": "acpi_gpio_in_ignore_list",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:208",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool acpi_gpio_in_ignore_list(const char * controller_in, int pin_in)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pin_in</code> ➡️ <code>unsigned int pin_in</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * ignore_list</code>
</li>
<li>
<b>Param reordered. </b>
<code>controller_in, pin_in</code> ➡️ <code>ignore_list, controller_in, pin_in</code>
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

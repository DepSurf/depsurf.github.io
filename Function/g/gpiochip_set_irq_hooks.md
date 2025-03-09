# Function: <code>gpiochip_set_irq_hooks</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584199584,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1829",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199584,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1893",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388768,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071584410982,
      "name": "gpiochip_set_irq_hooks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584548002,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2211",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584529552,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584548002,
      "name": "gpiochip_set_irq_hooks.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2541",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190672,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071585219201,
      "name": "gpiochip_set_irq_hooks.cold",
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
void gpiochip_set_irq_hooks(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1427",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349856,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071591385764,
      "name": "gpiochip_set_irq_hooks.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585235500,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1416",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip"
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
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585690810,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1438",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip"
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
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586858933,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1480",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip"
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
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588004775,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1550",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip"
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
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588280021,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1581",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip"
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
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588572048,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1762",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496705416,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2211",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496705416,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230005152,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2211",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230005152,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290793472,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2211",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290793472,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275474002,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2211",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275474002,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584504930,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2211",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486480,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584504930,
      "name": "gpiochip_set_irq_hooks.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584443058,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2211",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424608,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584443058,
      "name": "gpiochip_set_irq_hooks.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584499666,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2211",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584481216,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584499666,
      "name": "gpiochip_set_irq_hooks.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```

```json
{
  "name": "gpiochip_set_irq_hooks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584605938,
      "name": "gpiochip_set_irq_hooks",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2211",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587312,
      "name": "gpiochip_set_irq_hooks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584605938,
      "name": "gpiochip_set_irq_hooks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip * gpiochip)
```
</details>
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
<code>struct gpio_chip * gpiochip</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip * gc)
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

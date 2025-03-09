# Function: <code>gpiochip_irqchip_irq_valid</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583630443,
      "name": "gpiochip_irqchip_irq_valid",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_remove"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583669097,
      "name": "gpiochip_irqchip_irq_valid",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1494",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_remove"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583923362,
      "name": "gpiochip_irqchip_irq_valid",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1525",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_remove"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584114336,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1629",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114336,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197792,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1629",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197792,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387232,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1648",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387232,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584522528,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1671",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522528,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585198125,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2000",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201056,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585356125,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:947",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358464,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585239664,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:936",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239664,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585695040,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:958",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695040,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586862256,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:988",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586862256,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588008304,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1061",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588005440,
      "name": "gpiochip_irqchip_irq_valid.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071588013184,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588283454,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1091",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588278192,
      "name": "gpiochip_irqchip_irq_valid.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071588287744,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588576494,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1257",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588571312,
      "name": "gpiochip_irqchip_irq_valid.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071588580864,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496700176,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1671",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496700176,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229996212,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1671",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229996212,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290788416,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1671",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290788416,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275465674,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1671",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275465674,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584479456,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1671",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479456,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584417584,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1671",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417584,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584474192,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1671",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584474192,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_irqchip_irq_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584580320,
      "name": "gpiochip_irqchip_irq_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1671",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584580320,
      "name": "gpiochip_irqchip_irq_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct gpio_chip * gc</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct gpio_chip * gpiochip</code>
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

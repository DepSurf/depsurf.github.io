# Function: <code>gpiochip_reqres_irq</code>

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
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204496,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3532",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204496,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3621",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411247,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584393632,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3975",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584547810,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584527248,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int gpiochip_reqres_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585200104,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4388",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219924,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585200000,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int gpiochip_reqres_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585354664,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3212",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386218,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585354560,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int gpiochip_reqres_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585240904,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3189",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591328600,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585238496,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int gpiochip_reqres_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585696328,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3248",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592351351,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585694528,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int gpiochip_reqres_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586861864,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3369",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594212521,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586857104,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int gpiochip_reqres_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588002432,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3439",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002432,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int gpiochip_reqres_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588277408,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3480",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277408,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int gpiochip_reqres_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588569952,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3673",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588569952,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496717760,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3975",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496717760,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230001840,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3975",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230001840,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290796912,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3975",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290796912,
      "name": "gpiochip_reqres_irq",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275471290,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3975",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275471290,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3975",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504738,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584484176,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3975",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442866,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584422304,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3975",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499474,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584478912,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_reqres_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_reqres_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3975",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584605746,
      "name": "gpiochip_reqres_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584585024,
      "name": "gpiochip_reqres_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int gpiochip_reqres_irq(struct gpio_chip * chip, unsigned int offset)
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

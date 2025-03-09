# Function: <code>mctrl_gpio_get</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585748831,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:68",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585748640,
      "name": "mctrl_gpio_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585748752,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585891055,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890864,
      "name": "mctrl_gpio_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585890976,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586628368,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586628368,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586737712,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586737712,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586621328,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586621328,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587167040,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587167040,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588478272,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588478272,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589912896,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589912896,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590222064,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590222064,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590562784,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590562784,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498708024,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/imx.c:imx_uart_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498707200,
      "name": "mctrl_gpio_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446603336498707360,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231336444,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/imx.c:imx_uart_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231336208,
      "name": "mctrl_gpio_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 3231336336,
      "name": "mctrl_gpio_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291856876,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291856528,
      "name": "mctrl_gpio_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 13835058055291856752,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276227300,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276227062,
      "name": "mctrl_gpio_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446743936276227194,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585652047,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585651856,
      "name": "mctrl_gpio_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585651968,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585517119,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585516928,
      "name": "mctrl_gpio_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585517040,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585841455,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841264,
      "name": "mctrl_gpio_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585841376,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585949071,
      "name": "mctrl_gpio_get",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:76",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948880,
      "name": "mctrl_gpio_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585948992,
      "name": "mctrl_gpio_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios * gpios, unsigned int * mctrl)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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

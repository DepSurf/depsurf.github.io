# Function: <code>serial8250_handle_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584123952,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1555",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123952,
      "name": "serial8250_handle_irq.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071584124144,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584459377,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1812",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584459072,
      "name": "serial8250_handle_irq.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071584459312,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584641788,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1809",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584641248,
      "name": "serial8250_handle_irq.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071584641488,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584725324,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1827",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:exar_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:exar_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724848,
      "name": "serial8250_handle_irq.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071584725040,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585139720,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1858",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:exar_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:exar_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585139216,
      "name": "serial8250_handle_irq.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071585139424,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585373016,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1860",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585372608,
      "name": "serial8250_handle_irq.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071585372832,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585497032,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1859",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585496576,
      "name": "serial8250_handle_irq.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071585496848,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585710410,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1865",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585709952,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071585710224,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585851146,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1814",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585850688,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071585850960,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586579930,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1884",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586579312,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071586579696,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586690138,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1885",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586689520,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071586689904,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586573018,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1897",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572400,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071586572784,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587114810,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1898",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587114192,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071587114576,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588428920,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1913",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427952,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
    },
    {
      "addr": 18446744071588428672,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589857224,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1914",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:tng_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589856160,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
    },
    {
      "addr": 18446744071589856944,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590164928,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1903",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:tng_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590164928,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 839
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590502752,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1902",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:tng_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590502752,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498583344,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1814",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498580712,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446603336498581064,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231217232,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1814",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231216748,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 3231217012,
      "name": "serial8250_handle_irq",
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291803376,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1814",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291802640,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 13835058055291803072,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276184208,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1814",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276183746,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446743936276183988,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585612154,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1814",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585611696,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071585611968,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585477722,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1814",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585477264,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071585477536,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585801546,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1814",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585801088,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071585801360,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int serial8250_handle_irq(struct uart_port * port, unsigned int iir)
```

```json
{
  "name": "serial8250_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585909722,
      "name": "serial8250_handle_irq",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1814",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909264,
      "name": "serial8250_handle_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071585909536,
      "name": "serial8250_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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

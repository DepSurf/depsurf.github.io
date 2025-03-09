# Function: <code>serial8250_rpm_put_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584112768,
      "name": "serial8250_rpm_put_tx",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:549",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112768,
      "name": "serial8250_rpm_put_tx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584458686,
      "name": "serial8250_rpm_put_tx",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:651",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584634528,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:653",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634528,
      "name": "serial8250_rpm_put_tx.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071584636992,
      "name": "serial8250_rpm_put_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584715520,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:669",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714208,
      "name": "serial8250_rpm_put_tx.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071584715520,
      "name": "serial8250_rpm_put_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585128816,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:688",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585127408,
      "name": "serial8250_rpm_put_tx.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071585128816,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585364624,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:689",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363248,
      "name": "serial8250_rpm_put_tx.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071585364624,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585490320,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:689",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487632,
      "name": "serial8250_rpm_put_tx.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585490320,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585702560,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:697",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702560,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585843232,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:690",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843232,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586579225,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:725",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573456,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586689435,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:726",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586683664,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586572312,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:730",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567232,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587114057,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:731",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107328,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588427781,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:718",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588413344,
      "name": "serial8250_rpm_put_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589855621,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:712",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589840448,
      "name": "serial8250_rpm_put_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590165644,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:656",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149296,
      "name": "serial8250_rpm_put_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590503472,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:657",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590489440,
      "name": "serial8250_rpm_put_tx",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498574632,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:690",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498573296,
      "name": "serial8250_rpm_put_tx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336498574632,
      "name": "serial8250_rpm_put_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231210764,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:690",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231208636,
      "name": "serial8250_rpm_put_tx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3231210764,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291791696,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:690",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291791696,
      "name": "serial8250_rpm_put_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276177870,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:690",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276176742,
      "name": "serial8250_rpm_put_tx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446743936276177870,
      "name": "serial8250_rpm_put_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585604240,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:690",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604240,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585469328,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:690",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585469328,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585793632,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:690",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585793632,
      "name": "serial8250_rpm_put_tx",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_put_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585901344,
      "name": "serial8250_rpm_put_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:690",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585901344,
      "name": "serial8250_rpm_put_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port * p)
```
</details>
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

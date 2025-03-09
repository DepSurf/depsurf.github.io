# Function: <code>uart_write_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584092416,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:71",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092416,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584422672,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:106",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422672,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584605840,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:107",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584605840,
      "name": "uart_write_wakeup.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071584605856,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584687664,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:108",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687664,
      "name": "uart_write_wakeup.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071584687680,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585100176,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:95",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585100176,
      "name": "uart_write_wakeup.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071585100192,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585334112,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:95",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_wq_proc",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585334112,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585457424,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:95",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_wq_proc",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457424,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585673360,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:95",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673360,
      "name": "uart_write_wakeup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071585673376,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585814320,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:96",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814320,
      "name": "uart_write_wakeup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071585814336,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586544896,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:97",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586544896,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586655680,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:98",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586655680,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586539568,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:98",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539568,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587073632,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:98",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587073632,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588377344,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:104",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588377344,
      "name": "uart_write_wakeup",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589799840,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:111",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589799840,
      "name": "uart_write_wakeup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590105184,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:112",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590105184,
      "name": "uart_write_wakeup",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590444624,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:112",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590444624,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498535000,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:96",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/amba-pl011.c:pl011_tx_chars",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_txint",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx_callback",
        "drivers/tty/serial/meson_uart.c:meson_uart_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx_pio",
        "drivers/tty/serial/msm_serial.c:msm_complete_tx_dma",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498535000,
      "name": "uart_write_wakeup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336498535024,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231184488,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:96",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/amba-pl011.c:pl011_tx_chars",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_txint",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx_callback",
        "drivers/tty/serial/meson_uart.c:meson_uart_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx_pio",
        "drivers/tty/serial/msm_serial.c:msm_complete_tx_dma",
        "drivers/tty/serial/omap-serial.c:serial_omap_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/rda-uart.c:rda_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231184488,
      "name": "uart_write_wakeup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3231184512,
      "name": "uart_write_wakeup",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291743296,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:96",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291743296,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276153460,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:96",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sifive.c:sifive_serial_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276153460,
      "name": "uart_write_wakeup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446743936276153480,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585575312,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:96",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585575312,
      "name": "uart_write_wakeup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071585575328,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585440512,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:96",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440512,
      "name": "uart_write_wakeup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071585440528,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585764720,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:96",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585764720,
      "name": "uart_write_wakeup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071585764736,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void uart_write_wakeup(struct uart_port * port)
```

```json
{
  "name": "uart_write_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585874160,
      "name": "uart_write_wakeup",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:96",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874160,
      "name": "uart_write_wakeup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071585874176,
      "name": "uart_write_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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

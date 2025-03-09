# Function: <code>serial8250_rpm_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584118288,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:514",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584118288,
      "name": "serial8250_rpm_get.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584118320,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584460563,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:549",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452128,
      "name": "serial8250_rpm_get.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584452160,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584642771,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:550",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634416,
      "name": "serial8250_rpm_get.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584634448,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584725864,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:566",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714096,
      "name": "serial8250_rpm_get.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584714128,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585140248,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:583",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585127296,
      "name": "serial8250_rpm_get.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585127328,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585374328,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:584",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363136,
      "name": "serial8250_rpm_get.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585363168,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585498040,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:584",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487520,
      "name": "serial8250_rpm_get.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585487552,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585716312,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:592",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585700928,
      "name": "serial8250_rpm_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585700960,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585856936,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:585",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841648,
      "name": "serial8250_rpm_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585841680,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586582202,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:570",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573872,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586693354,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:571",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684080,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586575635,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:575",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567648,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587115582,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:576",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587108080,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588421515,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:563",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588414224,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589849115,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:563",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589841424,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590157825,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:503",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590150224,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590498017,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:504",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590490368,
      "name": "serial8250_rpm_get",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498590136,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:585",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498573192,
      "name": "serial8250_rpm_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336498573240,
      "name": "serial8250_rpm_get",
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231223160,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:585",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231208560,
      "name": "serial8250_rpm_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3231208596,
      "name": "serial8250_rpm_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291812680,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:585",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291789248,
      "name": "serial8250_rpm_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055291789312,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276189070,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:585",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276176562,
      "name": "serial8250_rpm_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446743936276176608,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585617944,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:585",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602656,
      "name": "serial8250_rpm_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585602688,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585483000,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:585",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585467744,
      "name": "serial8250_rpm_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585467776,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585807336,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:585",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585792048,
      "name": "serial8250_rpm_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585792080,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void serial8250_rpm_get(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585915000,
      "name": "serial8250_rpm_get",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:585",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899760,
      "name": "serial8250_rpm_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585899792,
      "name": "serial8250_rpm_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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

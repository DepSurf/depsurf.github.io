# Function: <code>tty_termios_baud_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583990112,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_termios_input_baud_rate"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_pci.c:byt_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990112,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584322331,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:309",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_termios_input_baud_rate"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_pci.c:byt_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322240,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584504363,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:309",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_termios_input_baud_rate"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504272,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584598683,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:60",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584598592,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585011131,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011040,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585245283,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245152,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585364544,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585364544,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585578240,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578240,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585719152,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719152,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586448944,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:57",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448944,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586563424,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:57",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586563424,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586448384,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:58",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448384,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974688,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:58",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974688,
      "name": "tty_termios_baud_rate",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271328,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:58",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271328,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
speed_t tty_termios_baud_rate(const struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589687595,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:58",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589686256,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
speed_t tty_termios_baud_rate(const struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589992203,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:58",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589990864,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
speed_t tty_termios_baud_rate(const struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590330731,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:58",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590329392,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498411632,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498411632,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231083416,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_termios",
        "drivers/tty/serial/rda-uart.c:rda_uart_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231083416,
      "name": "tty_termios_baud_rate",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291596208,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291596016,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276069178,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276069178,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585480176,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480176,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585350096,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350096,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669552,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669552,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
speed_t tty_termios_baud_rate(struct ktermios * termios)
```

```json
{
  "name": "tty_termios_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585777648,
      "name": "tty_termios_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:61",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_init_termios",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777648,
      "name": "tty_termios_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ktermios * termios</code> ➡️ <code>const struct ktermios * termios</code>
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

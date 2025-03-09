# Function: <code>tty_termios_encode_baud_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583990320,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:398",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ioctl.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990320,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322432,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:393",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ioctl.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322432,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584504464,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:393",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ioctl.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504464,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584598784,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:144",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584598784,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585011232,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011232,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245344,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245344,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585364752,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585364752,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585578464,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578464,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585719376,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719376,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586449184,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:141",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586449184,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586563664,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:141",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586563664,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586448608,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:142",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448608,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974960,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:142",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974960,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 937
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271696,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:137",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271696,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589686432,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:129",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589686432,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589991040,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:129",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589991040,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 969
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590329568,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:129",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590329568,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 969
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498411984,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios",
        "drivers/tty/serial/amba-pl011.c:sbsa_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498411984,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231083656,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios",
        "drivers/tty/serial/amba-pl011.c:sbsa_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_termios",
        "drivers/tty/serial/rda-uart.c:rda_uart_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231083656,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291596304,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ioctl.c:tty_mode_ioctl",
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291596304,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276069484,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276069484,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585480400,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480400,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585350320,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350320,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669776,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669776,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void tty_termios_encode_baud_rate(struct ktermios * termios, speed_t ibaud, speed_t obaud)
```

```json
{
  "name": "tty_termios_encode_baud_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585777872,
      "name": "tty_termios_encode_baud_rate",
      "external": true,
      "loc": "drivers/tty/tty_baudrate.c:145",
      "file": "drivers/tty/tty_baudrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_baudrate.c:tty_encode_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_set_options",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/serial_core.c:uart_get_baud_rate",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777872,
      "name": "tty_termios_encode_baud_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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

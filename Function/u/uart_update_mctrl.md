# Function: <code>uart_update_mctrl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584094763,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:114",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584417280,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:150",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417280,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584599680,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:151",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584599680,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584682224,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:152",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584682224,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585094528,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:139",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585094528,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585328528,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:139",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328528,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585451792,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:142",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451792,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667648,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:139",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667648,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808624,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:140",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808624,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586553542,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:141",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539888,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586664358,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:142",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586650864,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586546774,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:142",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534832,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587085558,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:142",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587073248,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376800,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:149",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376800,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589799184,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:156",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589799184,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590104528,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:178",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104528,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590443968,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:177",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590443968,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498538416,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:140",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498538416,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231175248,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:140",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231175248,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291742656,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:140",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291742656,
      "name": "uart_update_mctrl",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276148658,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:140",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276148658,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585569616,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:140",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585569616,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585434816,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:140",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434816,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585759024,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:140",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585759024,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```

```json
{
  "name": "uart_update_mctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585866928,
      "name": "uart_update_mctrl",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:140",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_tiocmset",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_port_dtr_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585866928,
      "name": "uart_update_mctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void uart_update_mctrl(struct uart_port * port, unsigned int set, unsigned int clear)
```
</details>
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

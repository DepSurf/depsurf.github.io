# Function: <code>serial8250_early_in</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595259190,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:40",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_write",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595259190,
      "name": "serial8250_early_in",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 87
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595440544,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:40",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595440544,
      "name": "serial8250_early_in",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 103
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595692896,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:40",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595692896,
      "name": "serial8250_early_in",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 103
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596617482,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:40",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596617482,
      "name": "serial8250_early_in",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585155872,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585155872,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585390000,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585390000,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585513456,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585513456,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585732320,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585732320,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585874384,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874384,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586609360,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586609360,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586719280,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719280,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602800,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602800,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587145792,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071592452886,
      "name": "serial8250_early_in.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455856,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    },
    {
      "addr": 18446744071594321223,
      "name": "serial8250_early_in.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886432,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    },
    {
      "addr": 18446744071596237117,
      "name": "serial8250_early_in.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590194624,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071596765134,
      "name": "serial8250_early_in.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:36",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_read",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590520832,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071597673710,
      "name": "serial8250_early_in.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498611888,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498611888,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231239476,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231239476,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291839968,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291839968,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276207368,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276207368,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585635376,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635376,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585500448,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585500448,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585824784,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824784,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
unsigned int serial8250_early_in(struct uart_port * port, int offset)
```

```json
{
  "name": "serial8250_early_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585932400,
      "name": "serial8250_early_in",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:37",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585932400,
      "name": "serial8250_early_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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

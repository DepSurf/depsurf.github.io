# Function: <code>serial8250_early_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595259313,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:56",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_write",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_write",
        "drivers/tty/serial/8250/8250_early.c:serial_putc",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595259313,
      "name": "serial8250_early_out",
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595440647,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595440647,
      "name": "serial8250_early_out",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595692999,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595692999,
      "name": "serial8250_early_out",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596617377,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:63",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596617377,
      "name": "serial8250_early_out",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 105
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585155744,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585155744,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585389872,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585389872,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585513312,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585513312,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585732176,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585732176,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585874240,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874240,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586609632,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586609632,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586719552,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:init_port",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719552,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586603072,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603072,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587146160,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071592452919,
      "name": "serial8250_early_out.cold",
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456304,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071594321256,
      "name": "serial8250_early_out.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886912,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071596237150,
      "name": "serial8250_early_out.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:57",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590195072,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071596765167,
      "name": "serial8250_early_out.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:56",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590521280,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071597673743,
      "name": "serial8250_early_out.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498611592,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498611592,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231239692,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231239692,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291839488,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291839488,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276207724,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276207724,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635232,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635232,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585500304,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585500304,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585824640,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824640,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void serial8250_early_out(struct uart_port * port, int offset, int value)
```

```json
{
  "name": "serial8250_early_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585932256,
      "name": "serial8250_early_out",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_setup",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585932256,
      "name": "serial8250_early_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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

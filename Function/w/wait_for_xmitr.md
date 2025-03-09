# Function: <code>wait_for_xmitr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584114864,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1717",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write"
      ]
    },
    {
      "addr": 18446744071595259277,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_early.c:76",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_early.c:early_serial8250_write",
        "drivers/tty/serial/8250/8250_early.c:serial_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114864,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071595259277,
      "name": "wait_for_xmitr",
      "section": ".init.text",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584448640,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1976",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584448640,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630928,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1997",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630928,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584712624,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2009",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584712624,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585125728,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2040",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585125728,
      "name": "wait_for_xmitr",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585361712,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2023",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585361712,
      "name": "wait_for_xmitr",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585485888,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2022",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485888,
      "name": "wait_for_xmitr",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585699312,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2014",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699312,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585840400,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1963",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585840400,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586572592,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2054",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572592,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586682800,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2055",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586682800,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586566368,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2068",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586566368,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587106672,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2062",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587106672,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588414512,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2096",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588414512,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589841776,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2100",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589841776,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590150848,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2093",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590150848,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590490992,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:2095",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590490992,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498571568,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1963",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    },
    {
      "addr": 18446603336498698272,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/mvebu-uart.c:643",
      "file": "drivers/tty/serial/mvebu-uart.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_putchar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498571568,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446603336498698272,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231207224,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1963",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    },
    {
      "addr": 3231319024,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/omap-serial.c:1164",
      "file": "drivers/tty/serial/omap-serial.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/omap-serial.c:serial_omap_console_write",
        "drivers/tty/serial/omap-serial.c:serial_omap_console_putchar",
        "drivers/tty/serial/omap-serial.c:serial_omap_poll_put_char"
      ]
    },
    {
      "addr": 3231323164,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/mvebu-uart.c:643",
      "file": "drivers/tty/serial/mvebu-uart.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_putchar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231207224,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 3231319024,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 3231323164,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291787248,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1963",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291787248,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276175360,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1963",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276175360,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585601408,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1963",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585601408,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585466496,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1963",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585466496,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585790800,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1963",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585790800,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void wait_for_xmitr(struct uart_8250_port * up, int bits)
```

```json
{
  "name": "wait_for_xmitr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585898512,
      "name": "wait_for_xmitr",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1963",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898512,
      "name": "wait_for_xmitr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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

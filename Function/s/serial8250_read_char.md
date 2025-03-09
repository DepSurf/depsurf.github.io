# Function: <code>serial8250_read_char</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584455028,
      "name": "serial8250_read_char",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1640",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584637316,
      "name": "serial8250_read_char",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1637",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584717252,
      "name": "serial8250_read_char",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1653",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585130644,
      "name": "serial8250_read_char",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1684",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585366384,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1685",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585366384,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585482784,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1684",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482784,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585698304,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1690",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585698304,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585839392,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1639",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585839392,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586571648,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1709",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586571648,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586681856,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1710",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586681856,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586565312,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1710",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586565312,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587105568,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1711",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587105568,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588411712,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1728",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588411712,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void serial8250_read_char(struct uart_8250_port * up, u16 lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589838560,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1725",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589838560,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
void serial8250_read_char(struct uart_8250_port * up, u16 lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590146512,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1703",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590146512,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
void serial8250_read_char(struct uart_8250_port * up, u16 lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590487632,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1703",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590487632,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498570344,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1639",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498570344,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231205724,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1639",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231205724,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291785248,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1639",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291785248,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276174592,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1639",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276174592,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585600400,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1639",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585600400,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585465488,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1639",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585465488,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585789792,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1639",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585789792,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```

```json
{
  "name": "serial8250_read_char",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585897504,
      "name": "serial8250_read_char",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:1639",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585897504,
      "name": "serial8250_read_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void serial8250_read_char(struct uart_8250_port * up, unsigned char lsr)
```
</details>
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
<code>unsigned char lsr</code> ➡️ <code>u16 lsr</code>
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

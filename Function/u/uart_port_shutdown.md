# Function: <code>uart_port_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584095751,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1532",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_shutdown"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584419657,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1630",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_shutdown"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601920,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1609",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601920,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584684400,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1615",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684400,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585096784,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1626",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585096784,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585330768,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1633",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585330768,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585454032,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1692",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454032,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669920,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1686",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669920,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585810864,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1685",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810864,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586541520,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1686",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586541520,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586652496,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1692",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652496,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586536464,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1691",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586536464,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587074880,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1690",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587074880,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588378864,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1724",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588378864,
      "name": "uart_port_shutdown",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589802592,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1841",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589802592,
      "name": "uart_port_shutdown",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590107936,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1862",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590107936,
      "name": "uart_port_shutdown",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590447472,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1898",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590447472,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498531848,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1685",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498531848,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231178892,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1685",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231178892,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291746560,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1685",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291746560,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276150560,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1685",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276150560,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585571856,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1685",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571856,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437056,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1685",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437056,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585761264,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1685",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585761264,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void uart_port_shutdown(struct tty_port * port)
```

```json
{
  "name": "uart_port_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869312,
      "name": "uart_port_shutdown",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1685",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869312,
      "name": "uart_port_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void uart_port_shutdown(struct tty_port * port)
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

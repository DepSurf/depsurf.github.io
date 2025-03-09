# Function: <code>serial8250_rpm_get_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584123708,
      "name": "serial8250_rpm_get_tx",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:536",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
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
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584460044,
      "name": "serial8250_rpm_get_tx",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:638",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584634416,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:639",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634416,
      "name": "serial8250_rpm_get_tx.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584634480,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584714160,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:655",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714096,
      "name": "serial8250_rpm_get_tx.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584714160,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585127360,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:674",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585127296,
      "name": "serial8250_rpm_get_tx.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585127360,
      "name": "serial8250_rpm_get_tx",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585363200,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:675",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363136,
      "name": "serial8250_rpm_get_tx.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585363200,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585487584,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:675",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487520,
      "name": "serial8250_rpm_get_tx.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585487584,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585700992,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:683",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585700992,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585841712,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:676",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841712,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586580008,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:711",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573808,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586690216,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:712",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684016,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586573096,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:716",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567584,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587114888,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:717",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107696,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588429048,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:704",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588413808,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589857368,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:698",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589840960,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590166136,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:642",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149920,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590503960,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:643",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590490064,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498575496,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:676",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498573192,
      "name": "serial8250_rpm_get_tx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336498575496,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231211076,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:676",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231208560,
      "name": "serial8250_rpm_get_tx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3231211076,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291789344,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:676",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291789344,
      "name": "serial8250_rpm_get_tx",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276176662,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:676",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276176562,
      "name": "serial8250_rpm_get_tx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446743936276176662,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585602720,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:676",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602720,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585467808,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:676",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585467808,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585792112,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:676",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585792112,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_rpm_get_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585899824,
      "name": "serial8250_rpm_get_tx",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:676",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899824,
      "name": "serial8250_rpm_get_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void serial8250_rpm_get_tx(struct uart_8250_port * p)
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

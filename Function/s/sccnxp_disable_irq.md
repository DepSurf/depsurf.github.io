# Function: <code>sccnxp_disable_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584148868,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:331",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584486020,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:331",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584668148,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:331",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584750196,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:331",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585165773,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:327",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585400973,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:327",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585524016,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585524016,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585742624,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742624,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585884864,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585884864,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586624079,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:362",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586733615,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:362",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586617247,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:362",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:362",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587164032,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071592453701,
      "name": "sccnxp_disable_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:362",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588475056,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071594322049,
      "name": "sccnxp_disable_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:362",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589909536,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071596237524,
      "name": "sccnxp_disable_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:362",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590218656,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071596765691,
      "name": "sccnxp_disable_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:362",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590559376,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071597674324,
      "name": "sccnxp_disable_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498674120,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498674120,
      "name": "sccnxp_disable_irq",
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231291972,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231291972,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291848864,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291848864,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276218614,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276218614,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585645856,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645856,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510928,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510928,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585835264,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585835264,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void sccnxp_disable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_disable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585942880,
      "name": "sccnxp_disable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:366",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942880,
      "name": "sccnxp_disable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void sccnxp_disable_irq(struct uart_port * port, int mask)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void sccnxp_disable_irq(struct uart_port * port, int mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void sccnxp_disable_irq(struct uart_port * port, int mask)
```
</details>
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

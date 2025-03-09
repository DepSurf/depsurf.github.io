# Function: <code>uart_set_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584100384,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:729",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
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
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584433704,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:786",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
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
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584616952,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:778",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
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
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584698624,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:779",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
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
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585111112,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:787",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
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
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585346867,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:794",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585468309,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:810",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585684016,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:804",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585684016,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1466
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585825008,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:805",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825008,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1548
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586554352,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:806",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586554352,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1567
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586665168,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:807",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586665168,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1567
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586547712,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:805",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586547712,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1492
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587088848,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:788",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587088848,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1492
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394960,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:800",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394960,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1496
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589820080,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:806",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589820080,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590125536,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:827",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590125536,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590467488,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:821",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590467488,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498549016,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:805",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498549016,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231194204,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:805",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231194204,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1396
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291767088,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:805",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291767088,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1720
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276161380,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:805",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276161380,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585586000,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:805",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585586000,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1548
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585451936,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:805",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451936,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1548
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585775408,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:805",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585775408,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1548
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
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```

```json
{
  "name": "uart_set_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585884784,
      "name": "uart_set_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:805",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585884784,
      "name": "uart_set_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1548
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int uart_set_info(struct tty_struct * tty, struct tty_port * port, struct uart_state * state, struct serial_struct * new_info)
```
</details>
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

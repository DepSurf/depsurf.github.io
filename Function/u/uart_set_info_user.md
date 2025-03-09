# Function: <code>uart_set_info_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584100314,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:921",
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
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584433625,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:981",
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
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584616873,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:976",
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
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584698567,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:982",
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
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585111063,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:992",
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
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585346818,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:999",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585468240,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1015",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585468240,
      "name": "uart_set_info_user",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585685488,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1009",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585685488,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585826560,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1008",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826560,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586555920,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1009",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586555920,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666736,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1010",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666736,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586549216,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1009",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586549216,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587090352,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:992",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587090352,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588396464,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1004",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588396464,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589821520,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1010",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589821520,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590126976,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1031",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590126976,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590468928,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1025",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590468928,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498550384,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1008",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498550384,
      "name": "uart_set_info_user",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231195600,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1008",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231195600,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291768816,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1008",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291768816,
      "name": "uart_set_info_user",
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276162520,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1008",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276162520,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585587552,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1008",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585587552,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585453488,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1008",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585453488,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776960,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1008",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776960,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_set_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585886336,
      "name": "uart_set_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:1008",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585886336,
      "name": "uart_set_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int uart_set_info_user(struct tty_struct * tty, struct serial_struct * ss)
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

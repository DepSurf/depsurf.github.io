# Function: <code>uart_port_startup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584099418,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:134",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584432829,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:170",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_startup"
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
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584616316,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:171",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584697996,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:172",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585109733,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:180",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585342613,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:180",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585467493,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:183",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585683301,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:180",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585824293,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:181",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586553792,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:182",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_do_autoconfig",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553792,
      "name": "uart_port_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586664608,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:183",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_do_autoconfig",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664608,
      "name": "uart_port_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586547024,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:183",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586547024,
      "name": "uart_port_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587086528,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:183",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587086528,
      "name": "uart_port_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392624,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:182",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392624,
      "name": "uart_port_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817536,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:184",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_port_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817536,
      "name": "uart_port_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, bool init_hw)
```

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590122976,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:251",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_port_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590122976,
      "name": "uart_port_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, bool init_hw)
```

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590464928,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:250",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_port_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590464928,
      "name": "uart_port_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498543872,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:181",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231193476,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:181",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291766016,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:181",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276160810,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:181",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276160810,
      "name": "uart_port_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585585285,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:181",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585451221,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:181",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585774693,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:181",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_port_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585884069,
      "name": "uart_port_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:181",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int init_hw</code> ➡️ <code>bool init_hw</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int uart_port_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```
</details>
</li>
</ul>

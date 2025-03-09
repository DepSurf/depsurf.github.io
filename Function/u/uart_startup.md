# Function: <code>uart_startup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584099392,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:195",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_open",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_open",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099392,
      "name": "uart_startup.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
int uart_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584432768,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:229",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_open",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432768,
      "name": "uart_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584618610,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:230",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584616288,
      "name": "uart_startup.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584698957,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:231",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584697968,
      "name": "uart_startup.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585112073,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:239",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585109712,
      "name": "uart_startup.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585348575,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:243",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585342608,
      "name": "uart_startup.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585470603,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:251",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585467488,
      "name": "uart_startup.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585686528,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:248",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683296,
      "name": "uart_startup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585827600,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:249",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824288,
      "name": "uart_startup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586556413,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:250",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_do_autoconfig",
        "drivers/tty/serial/serial_core.c:uart_do_autoconfig",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info"
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
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586667229,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:251",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_do_autoconfig",
        "drivers/tty/serial/serial_core.c:uart_do_autoconfig",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info"
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
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586551032,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:251",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587088095,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:255",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588394136,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:254",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int uart_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589821707,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:256",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_port_activate",
        "drivers/tty/serial/serial_core.c:uart_port_activate"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589818224,
      "name": "uart_startup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int uart_startup(struct tty_struct * tty, struct uart_state * state, bool init_hw)
```

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590127163,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:323",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_port_activate",
        "drivers/tty/serial/serial_core.c:uart_port_activate"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590123664,
      "name": "uart_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int uart_startup(struct tty_struct * tty, struct uart_state * state, bool init_hw)
```

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590469115,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:322",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_port_activate",
        "drivers/tty/serial/serial_core.c:uart_port_activate"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590465616,
      "name": "uart_startup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498556148,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:249",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498543832,
      "name": "uart_startup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231196752,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:249",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231193456,
      "name": "uart_startup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291770036,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:249",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291765984,
      "name": "uart_startup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276164102,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:249",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585588592,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:249",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585585280,
      "name": "uart_startup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585454528,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:249",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451216,
      "name": "uart_startup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585778000,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:249",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585774688,
      "name": "uart_startup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585887376,
      "name": "uart_startup",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:249",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585884064,
      "name": "uart_startup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int uart_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int uart_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int uart_startup(struct tty_struct * tty, struct uart_state * state, int init_hw)
```
</details>
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

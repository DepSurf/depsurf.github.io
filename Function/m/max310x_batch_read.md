# Function: <code>max310x_batch_read</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585397824,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:612",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585397824,
      "name": "max310x_batch_read.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585521232,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:618",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521232,
      "name": "max310x_batch_read.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585737376,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_port_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585737376,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585879616,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_port_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585879616,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611616,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611616,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721760,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721760,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586605264,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586605264,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587148448,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587148448,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588460688,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460688,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589892477,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:657",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_handle_rx"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590201479,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:662",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_handle_rx"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590542706,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:678",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_handle_rx"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498646568,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_port_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498646568,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231269808,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_port_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231269808,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276215950,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_port_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276215950,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585640608,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_port_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640608,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585505680,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_port_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505680,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585830016,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_port_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585830016,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585937632,
      "name": "max310x_batch_read",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:639",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_port_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585937632,
      "name": "max310x_batch_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void max310x_batch_read(struct uart_port * port, u8 * rxbuf, unsigned int len)
```
</details>
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

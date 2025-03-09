# Function: <code>max310x_batch_write</code>

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
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585397200,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:597",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_wq_proc",
        "drivers/tty/serial/max310x.c:max310x_wq_proc",
        "drivers/tty/serial/max310x.c:max310x_wq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585397200,
      "name": "max310x_batch_write.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585520608,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:603",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_wq_proc",
        "drivers/tty/serial/max310x.c:max310x_wq_proc",
        "drivers/tty/serial/max310x.c:max310x_wq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520608,
      "name": "max310x_batch_write.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585736816,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585736816,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585879056,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585879056,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611840,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611840,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721536,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721536,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586605024,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586605024,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587148208,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587148208,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588460416,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460416,
      "name": "max310x_batch_write",
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
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589893263,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:650",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx"
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
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590202444,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:655",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx"
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
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590543628,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:671",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx",
        "drivers/tty/serial/max310x.c:max310x_handle_tx"
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498645944,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498645944,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231269176,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231269176,
      "name": "max310x_batch_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276215478,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276215478,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585640048,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640048,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585505120,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505120,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585829456,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585829456,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
```

```json
{
  "name": "max310x_batch_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585937072,
      "name": "max310x_batch_write",
      "external": false,
      "loc": "drivers/tty/serial/max310x.c:624",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc",
        "drivers/tty/serial/max310x.c:max310x_tx_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585937072,
      "name": "max310x_batch_write",
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
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
void max310x_batch_write(struct uart_port * port, u8 * txbuf, unsigned int len)
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

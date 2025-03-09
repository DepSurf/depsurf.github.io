# Function: <code>sccnxp_enable_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584147533,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:323",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584485837,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:323",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584667965,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:323",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584750014,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:323",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585165591,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:319",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585400791,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:319",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585524096,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585524096,
      "name": "sccnxp_enable_irq",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585742688,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742688,
      "name": "sccnxp_enable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585884928,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585884928,
      "name": "sccnxp_enable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586621569,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:354",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586731217,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:354",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586614785,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:354",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587158173,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:354",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588468749,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:354",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589902925,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:354",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590212125,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:354",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590552765,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:354",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498674208,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498674208,
      "name": "sccnxp_enable_irq",
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231292036,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231292036,
      "name": "sccnxp_enable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291848928,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291848928,
      "name": "sccnxp_enable_irq",
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276218696,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276218696,
      "name": "sccnxp_enable_irq",
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585645920,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645920,
      "name": "sccnxp_enable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510992,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510992,
      "name": "sccnxp_enable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585835328,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585835328,
      "name": "sccnxp_enable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
```

```json
{
  "name": "sccnxp_enable_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585942944,
      "name": "sccnxp_enable_irq",
      "external": false,
      "loc": "drivers/tty/serial/sccnxp.c:358",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942944,
      "name": "sccnxp_enable_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
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
void sccnxp_enable_irq(struct uart_port * port, int mask)
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

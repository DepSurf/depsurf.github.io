# Function: <code>__stop_tx_rs485</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584458514,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1441",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
void __stop_tx_rs485(struct uart_8250_port * p)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584639968,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1440",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584639968,
      "name": "__stop_tx_rs485",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __stop_tx_rs485(struct uart_8250_port * p)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584723136,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1456",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584723136,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void __stop_tx_rs485(struct uart_8250_port * p)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585137392,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1486",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585137392,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void __stop_tx_rs485(struct uart_8250_port * p)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585371584,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1487",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585371584,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585496078,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1486",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585709451,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1494",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585850187,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1443",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __stop_tx_rs485(struct uart_8250_port * p)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586574224,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1496",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586574224,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
void __stop_tx_rs485(struct uart_8250_port * p)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586684432,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1497",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684432,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
void __stop_tx_rs485(struct uart_8250_port * p)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586565968,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1498",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586565968,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void __stop_tx_rs485(struct uart_8250_port * p)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587106224,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1499",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587106224,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void __stop_tx_rs485(struct uart_8250_port * p, u64 stop_delay)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588412368,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1486",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588412368,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void __stop_tx_rs485(struct uart_8250_port * p, u64 stop_delay)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589839264,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1486",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589839264,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void __stop_tx_rs485(struct uart_8250_port * p, u64 stop_delay)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590147280,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1454",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590147280,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void __stop_tx_rs485(struct uart_8250_port * p, u64 stop_delay)
```

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590488416,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1454",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590488416,
      "name": "__stop_tx_rs485",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498577556,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1443",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231216228,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1443",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291801852,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1443",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276183348,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1443",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585611195,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1443",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585476763,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1443",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585800587,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1443",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__stop_tx_rs485",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585908763,
      "name": "__stop_tx_rs485",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1443",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void __stop_tx_rs485(struct uart_8250_port * p)
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void __stop_tx_rs485(struct uart_8250_port * p)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __stop_tx_rs485(struct uart_8250_port * p)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 stop_delay</code>
</li>
</ul>
</details>
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

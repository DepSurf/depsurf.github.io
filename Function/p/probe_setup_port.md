# Function: <code>probe_setup_port</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584647437,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:259",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584730438,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:290",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585145398,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:384",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585379557,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:384",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585502997,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:384",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585721269,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:385",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585862629,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:385",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586596416,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:393",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586596416,
      "name": "probe_setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
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
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586706784,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:393",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586706784,
      "name": "probe_setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
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
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586590368,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:393",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590368,
      "name": "probe_setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
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
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587131568,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:374",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131568,
      "name": "probe_setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1258
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
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588440656,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:374",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588440656,
      "name": "probe_setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589869696,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:360",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589869696,
      "name": "probe_setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590178528,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:360",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590178528,
      "name": "probe_setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1228
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
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590518688,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:360",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590518688,
      "name": "probe_setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1228
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
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498596320,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:385",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498596320,
      "name": "probe_setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```

```json
{
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276192946,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:385",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276192946,
      "name": "probe_setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585623637,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:385",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585488693,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:385",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585813029,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:385",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
  "name": "probe_setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585920645,
      "name": "probe_setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:385",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int probe_setup_port(struct fintek_8250 * pdata, struct uart_8250_port * uart)
```
</details>
</li>
</ul>

# Function: <code>uart_get_rs485_mode</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585333600,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3030",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585333600,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585456912,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3091",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456912,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672816,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3098",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672816,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585813776,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3100",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813776,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int uart_get_rs485_mode(struct uart_port * port)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3213",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562233,
      "name": "uart_get_rs485_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586544448,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int uart_get_rs485_mode(struct uart_port * port)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586655232,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3220",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586655232,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int uart_get_rs485_mode(struct uart_port * port)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586539120,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3217",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539120,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int uart_get_rs485_mode(struct uart_port * port)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587077536,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3234",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077536,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int uart_get_rs485_mode(struct uart_port * port)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588382752,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3275",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588382752,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int uart_get_rs485_mode(struct uart_port * port)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589806704,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3412",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589806704,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int uart_get_rs485_mode(struct uart_port * port)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590111472,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3564",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590111472,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int uart_get_rs485_mode(struct uart_port * port)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590450800,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3601",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590450800,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498534456,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3100",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/imx.c:imx_uart_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498534456,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231183920,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3100",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231183920,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291750432,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3100",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291750432,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276152982,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3100",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276152982,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585574768,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3100",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585574768,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585439968,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3100",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585439968,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585764176,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3100",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585764176,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```

```json
{
  "name": "uart_get_rs485_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585872384,
      "name": "uart_get_rs485_mode",
      "external": true,
      "loc": "drivers/tty/serial/serial_core.c:3100",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585872384,
      "name": "uart_get_rs485_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void uart_get_rs485_mode(struct device * dev, struct serial_rs485 * rs485conf)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct uart_port * port</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct serial_rs485 * rs485conf</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
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

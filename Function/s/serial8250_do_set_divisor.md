# Function: <code>serial8250_do_set_divisor</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585487040,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2580",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487040,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585700464,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2572",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585700464,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585838816,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2502",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585838816,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586571136,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2584",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_restore",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586571136,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586681344,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2585",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_restore",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586681344,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586564960,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2598",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586564960,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587104304,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2618",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587104304,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588410256,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2624",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588410256,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589836848,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2628",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589836848,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590145952,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2642",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590145952,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590486080,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2644",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590486080,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498569432,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2502",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498569432,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231205068,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2502",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231205068,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291784272,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2502",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291784272,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276173764,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2502",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276173764,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585599824,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2502",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585599824,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585464912,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2502",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585464912,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585789216,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2502",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585789216,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
```

```json
{
  "name": "serial8250_do_set_divisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585896928,
      "name": "serial8250_do_set_divisor",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_port.c:2502",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896928,
      "name": "serial8250_do_set_divisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void serial8250_do_set_divisor(struct uart_port * port, unsigned int baud, unsigned int quot, unsigned int quot_frac)
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

# Function: <code>fintek_8250_set_termios</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585144576,
      "name": "fintek_8250_set_termios",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144576,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585378752,
      "name": "fintek_8250_set_termios",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585378752,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585502192,
      "name": "fintek_8250_set_termios",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585502192,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720912,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071585722304,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585862272,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071585863664,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:312",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586595936,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    },
    {
      "addr": 18446744071586598261,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:312",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586706304,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    },
    {
      "addr": 18446744071591460586,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:312",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589888,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    },
    {
      "addr": 18446744071591402154,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:293",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587130832,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
    },
    {
      "addr": 18446744071592452131,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:293",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588439968,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
    },
    {
      "addr": 18446744071594320599,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, const struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589868640,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:279",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868640,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, const struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590177472,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:279",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590177472,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, const struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590517632,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:279",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590517632,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498595912,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498595912,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276194540,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276194540,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623280,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071585624672,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585488336,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071585489728,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585812672,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071585814064,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```

```json
{
  "name": "fintek_8250_set_termios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fintek_8250_set_termios",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_fintek.c:306",
      "file": "drivers/tty/serial/8250/8250_fintek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585920288,
      "name": "fintek_8250_set_termios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071585921680,
      "name": "fintek_8250_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ktermios * old</code> ➡️ <code>const struct ktermios * old</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void fintek_8250_set_termios(struct uart_port * port, struct ktermios * termios, struct ktermios * old)
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

# Function: <code>autoconfig</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584117052,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1067",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
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
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584450879,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1163",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
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
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584633167,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1166",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
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
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584717970,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1182",
      "file": "drivers/tty/serial/8250/8250_port.c",
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
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585131394,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1201",
      "file": "drivers/tty/serial/8250/8250_port.c",
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
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585369559,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1202",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
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
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585493205,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1202",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1210",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713696,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1421
    },
    {
      "addr": 18446744071585717391,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1159",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585854320,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1421
    },
    {
      "addr": 18446744071585858015,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1197",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589664,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
    },
    {
      "addr": 18446744071586592234,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1198",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586700352,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
    },
    {
      "addr": 18446744071591460558,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1202",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586582832,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1383
    },
    {
      "addr": 18446744071591402127,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1203",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123424,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1491
    },
    {
      "addr": 18446744071592451966,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1190",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588431568,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1505
    },
    {
      "addr": 18446744071594320432,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589859392,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1193",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859392,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1460
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590168160,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1147",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590168160,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1463
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590505984,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1147",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590505984,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1463
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498587576,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1159",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498587576,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231220776,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1159",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231220776,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1260
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291808848,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1159",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291808848,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1908
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276187136,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1159",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276187136,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1159",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615328,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1421
    },
    {
      "addr": 18446744071585619023,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1159",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480384,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1421
    },
    {
      "addr": 18446744071585484079,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1159",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804720,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1421
    },
    {
      "addr": 18446744071585808415,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void autoconfig(struct uart_8250_port * up)
```

```json
{
  "name": "autoconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "autoconfig",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:1159",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585912384,
      "name": "autoconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1421
    },
    {
      "addr": 18446744071585916079,
      "name": "autoconfig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void autoconfig(struct uart_8250_port * up)
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

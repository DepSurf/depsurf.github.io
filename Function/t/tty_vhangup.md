# Function: <code>tty_vhangup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583962912,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:799",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:tty_ioctl"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962912,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584302441,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:805",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584295760,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584484500,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:805",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584477824,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584562810,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:670",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584561536,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584973674,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:682",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972368,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585209583,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:691",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585206912,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585327716,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:692",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324576,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585540207,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:694",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585536496,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585681119,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:694",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677376,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586407753,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:695",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586405760,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586525004,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:693",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586521888,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586410299,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:709",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586407536,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586937108,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:708",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586934320,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588228492,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:704",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588226240,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589639120,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:698",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589636688,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589942530,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:699",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:serial_core_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589940320,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590280928,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:697",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:serial_core_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590281488,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498356884,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:694",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498353800,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231043396,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:694",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231039740,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291539292,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:694",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291536288,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276035030,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:694",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276032732,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585442143,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:694",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585438400,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585312175,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:694",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585308432,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585631519,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:694",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585627776,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void tty_vhangup(struct tty_struct * tty)
```

```json
{
  "name": "tty_vhangup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585737050,
      "name": "tty_vhangup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:694",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585735312,
      "name": "tty_vhangup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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

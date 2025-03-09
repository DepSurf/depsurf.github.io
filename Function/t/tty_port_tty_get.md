# Function: <code>tty_port_tty_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584004704,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:169",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584004704,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336224,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:169",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_wakeup",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336224,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584518064,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:169",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_wakeup",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518064,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584594304,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:282",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594304,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585009888,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009888,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585244016,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585244016,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585363440,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:282",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363440,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585577088,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:282",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585577088,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585718048,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718048,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586445872,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586445872,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586560176,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586560176,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586445136,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:284",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586445136,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586971568,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:284",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586971568,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588267760,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:301",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588267760,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589682480,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:322",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589682480,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589987088,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:322",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:serial_core_remove_one_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589987088,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590325600,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:322",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:serial_core_remove_one_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590325600,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498406152,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498406152,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231079452,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231079452,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291588400,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvsi_lib.c:hvsilib_open",
        "drivers/tty/hvc/hvsi.c:hvsi_interrupt",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291588400,
      "name": "tty_port_tty_get",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276064368,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276064368,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585479072,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585479072,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585348992,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348992,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585668448,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668448,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct tty_struct * tty_port_tty_get(struct tty_port * port)
```

```json
{
  "name": "tty_port_tty_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776544,
      "name": "tty_port_tty_get",
      "external": true,
      "loc": "drivers/tty/tty_port.c:283",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776544,
      "name": "tty_port_tty_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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

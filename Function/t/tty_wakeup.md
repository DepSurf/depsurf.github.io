# Function: <code>tty_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583955360,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:586",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_tty_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955360,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584287072,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:593",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_tty_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287072,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584469168,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:593",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_tty_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469168,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584554368,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:512",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584554368,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584965376,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:524",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584965376,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585198896,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:524",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585198896,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585317600,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:525",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317600,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585530416,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:527",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585530416,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585671296,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:527",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671296,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586397120,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:528",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:start_tty",
        "drivers/tty/n_tty.c:n_tty_check_unthrottle",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397120,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586512144,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:525",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:start_tty",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586512144,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586397312,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:526",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:start_tty",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397312,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586924016,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:526",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586924016,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588217760,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:522",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588217760,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589627104,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:516",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589627104,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589930800,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:517",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589930800,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590269312,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:515",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590269312,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498342352,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:527",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498342352,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231033856,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:527",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231033856,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291525248,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:527",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291525248,
      "name": "tty_wakeup",
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276024882,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:527",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276024882,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432320,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:527",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432320,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585302368,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:527",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585302368,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585621696,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:527",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585621696,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void tty_wakeup(struct tty_struct * tty)
```

```json
{
  "name": "tty_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585730016,
      "name": "tty_wakeup",
      "external": true,
      "loc": "drivers/tty/tty_io.c:527",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585730016,
      "name": "tty_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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

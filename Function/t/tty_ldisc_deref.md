# Function: <code>tty_ldisc_deref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583996048,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:300",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_buffer.c:flush_to_ldisc",
        "drivers/tty/pty.c:pty_flush_buffer",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996048,
      "name": "tty_ldisc_deref",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584330029,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:311",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_buffer.c:flush_to_ldisc",
        "drivers/tty/pty.c:pty_flush_buffer",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584328048,
      "name": "tty_ldisc_deref",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584511965,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:311",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_buffer.c:flush_to_ldisc",
        "drivers/tty/pty.c:pty_flush_buffer",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584510000,
      "name": "tty_ldisc_deref",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584591661,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:314",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589328,
      "name": "tty_ldisc_deref",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585003795,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:315",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585001440,
      "name": "tty_ldisc_deref",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585237924,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:301",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585235712,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585357236,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:301",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354960,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585570645,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:310",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585568288,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585711749,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:310",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585709408,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586440902,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:305",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tiocsti",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586438704,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586555430,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:304",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tiocsti",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553232,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586440406,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:305",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586438192,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586966214,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:290",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963904,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588261557,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:280",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588259296,
      "name": "tty_ldisc_deref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589675157,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:280",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_lookahead_buf",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589672608,
      "name": "tty_ldisc_deref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589979573,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:279",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_lookahead_buf",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589976800,
      "name": "tty_ldisc_deref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590318293,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:279",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_lookahead_buf",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590315472,
      "name": "tty_ldisc_deref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498400168,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:310",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498396536,
      "name": "tty_ldisc_deref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231075240,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:310",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231072952,
      "name": "tty_ldisc_deref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291583688,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:310",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291579872,
      "name": "tty_ldisc_deref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276061306,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:310",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276059024,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585472773,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:310",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470432,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585342789,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:310",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340448,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585662149,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:310",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659808,
      "name": "tty_ldisc_deref",
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
void tty_ldisc_deref(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_deref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585770261,
      "name": "tty_ldisc_deref",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:310",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_flush"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_wakeup",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:tty_set_termios",
        "drivers/tty/tty_port.c:tty_port_default_receive_buf",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_handle_dcd_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767920,
      "name": "tty_ldisc_deref",
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

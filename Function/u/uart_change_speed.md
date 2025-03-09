# Function: <code>uart_change_speed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584098704,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:443",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_resume_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584098704,
      "name": "uart_change_speed.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584432160,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:481",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432160,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584615680,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:473",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584615680,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584697344,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:474",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584697344,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585109072,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:482",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585109072,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585341280,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:489",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341280,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585465808,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:502",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585465808,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585681728,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:499",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681728,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585822720,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:500",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822720,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586547792,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:501",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586547792,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586658576,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:502",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586658576,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586546288,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:502",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586546288,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587085072,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:485",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587085072,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588383328,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:483",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588383328,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, const struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589808016,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:489",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589808016,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498539144,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:500",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498539144,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231175540,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:500",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231175540,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291759712,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:500",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291759712,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276160216,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:500",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_port_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276160216,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585583712,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:500",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585583712,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585447200,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:500",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447200,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585773120,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:500",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773120,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```

```json
{
  "name": "uart_change_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585873280,
      "name": "uart_change_speed",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:500",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_set_termios",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585873280,
      "name": "uart_change_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, struct ktermios * old_termios)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ktermios * old_termios</code> ➡️ <code>const struct ktermios * old_termios</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void uart_change_speed(struct tty_struct * tty, struct uart_state * state, const struct ktermios * old_termios)
```
</details>
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

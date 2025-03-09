# Function: <code>tty_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587382096,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:33",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382096,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336480,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:35",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336480,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584518320,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:35",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518320,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597728,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:35",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597728,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585010080,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585010080,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585244208,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585244208,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585363632,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363632,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585577328,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585577328,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585718240,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718240,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586447920,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tiocsctty",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447920,
      "name": "tty_unlock",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586562400,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tiocsctty",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562400,
      "name": "tty_unlock",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586447360,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:37",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447360,
      "name": "tty_unlock",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586974028,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:37",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_unlock_slave"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973600,
      "name": "tty_unlock",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588270555,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:37",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_unlock_slave"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270048,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589685371,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:33",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_unlock_slave"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589684944,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589989979,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:33",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_unlock_slave"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589989552,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590328507,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:33",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_mutex.c:tty_unlock_slave"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590328080,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498409984,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498409984,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231082184,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231082184,
      "name": "tty_unlock",
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291594512,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291594512,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276068106,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276068106,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585479264,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585479264,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585349184,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349184,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585668640,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668640,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void tty_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776736,
      "name": "tty_unlock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:36",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776736,
      "name": "tty_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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

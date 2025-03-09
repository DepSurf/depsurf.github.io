# Function: <code>tty_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587382176,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:13",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382176,
      "name": "tty_lock",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336560,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:13",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336560,
      "name": "tty_lock",
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584518400,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:13",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518400,
      "name": "tty_lock",
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597664,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:13",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597664,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585010144,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585010144,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585244272,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585244272,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585363696,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363696,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585577408,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585577408,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585718320,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718320,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586448000,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tiocsctty",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448000,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586562480,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tiocsctty",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562480,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586447440,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:15",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447440,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586973680,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:15",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973680,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588270144,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:15",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270144,
      "name": "tty_lock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589685008,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:15",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589685008,
      "name": "tty_lock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589989616,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:15",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589989616,
      "name": "tty_lock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590328144,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:15",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590328144,
      "name": "tty_lock",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498409880,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498409880,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231082068,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231082068,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291594368,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291594368,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276068008,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276068008,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585479344,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585479344,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585349264,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349264,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585668720,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668720,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void tty_lock(struct tty_struct * tty)
```

```json
{
  "name": "tty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776816,
      "name": "tty_lock",
      "external": true,
      "loc": "drivers/tty/tty_mutex.c:14",
      "file": "drivers/tty/tty_mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write_message",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_mutex.c:tty_lock_slave",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776816,
      "name": "tty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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

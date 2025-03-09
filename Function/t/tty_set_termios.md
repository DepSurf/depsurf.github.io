# Function: <code>tty_set_termios</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583991552,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:542",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991552,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584323664,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:535",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584323664,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584505648,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:535",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505648,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584585024,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:313",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584585024,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584997104,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584997104,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585231392,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585231392,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585350688,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350688,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567737,
      "name": "tty_set_termios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585563856,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585704992,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704992,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586434160,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586434160,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586548864,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586548864,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586433824,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586433824,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586959648,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:338",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959648,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588254720,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:338",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588254720,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589667520,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:341",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667520,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589971392,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:342",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589971392,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590310032,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:323",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/tty_ioctl.c:set_termios",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590310032,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498385208,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498385208,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231067036,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231067036,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291571440,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ioctl.c:tty_mode_ioctl",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291571440,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276054772,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276054772,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585466016,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585466016,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585336048,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585336048,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585655392,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585655392,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int tty_set_termios(struct tty_struct * tty, struct ktermios * new_termios)
```

```json
{
  "name": "tty_set_termios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585763504,
      "name": "tty_set_termios",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:314",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585763504,
      "name": "tty_set_termios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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

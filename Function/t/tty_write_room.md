# Function: <code>tty_write_room</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583990048,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:75",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990048,
      "name": "tty_write_room",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322176,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:75",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322176,
      "name": "tty_write_room",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584504208,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:75",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504208,
      "name": "tty_write_room",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584584080,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:75",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584080,
      "name": "tty_write_room",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584996128,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996128,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585230304,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585230304,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585349600,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349600,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585562768,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585562768,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585703904,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585703904,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586432720,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/n_tty.c:process_output_block",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586432720,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586547776,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/n_tty.c:process_output_block",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586547776,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586432928,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/n_tty.c:process_output_block",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586432928,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
unsigned int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586958704,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/n_tty.c:process_output_block",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586958704,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
unsigned int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588253600,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/n_tty.c:process_output_block",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588253600,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
unsigned int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589666256,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:77",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/n_tty.c:process_output_block",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589666256,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
unsigned int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589970144,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:78",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/n_tty.c:process_output_block",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589970144,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
unsigned int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590308784,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:66",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/n_tty.c:process_output_block",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590308784,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498384280,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498384280,
      "name": "tty_write_room",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231065972,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231065972,
      "name": "tty_write_room",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291570240,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291570240,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276053898,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276053898,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585464928,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585464928,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585334960,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585334960,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585654304,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585654304,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int tty_write_room(struct tty_struct * tty)
```

```json
{
  "name": "tty_write_room",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585762432,
      "name": "tty_write_room",
      "external": true,
      "loc": "drivers/tty/tty_ioctl.c:76",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:__process_echoes",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585762432,
      "name": "tty_write_room",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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

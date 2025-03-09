# Function: <code>tty_ldisc_ref_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995872,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:262",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995872,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584327968,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:272",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584327968,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584509920,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:272",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584509920,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584589232,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:272",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589232,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585001344,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:273",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585001344,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585235616,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:259",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585235616,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585354864,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:259",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354864,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585568192,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:268",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585568192,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585709312,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:268",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585709312,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586438608,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:263",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tiocsti",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586438608,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586553136,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:262",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tiocsti",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553136,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586438096,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:263",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586438096,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586963808,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:248",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963808,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588259184,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:240",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588259184,
      "name": "tty_ldisc_ref_wait",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589672480,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:240",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589672480,
      "name": "tty_ldisc_ref_wait",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589976672,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:239",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589976672,
      "name": "tty_ldisc_ref_wait",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590315344,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:239",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590315344,
      "name": "tty_ldisc_ref_wait",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498396448,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:268",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498396448,
      "name": "tty_ldisc_ref_wait",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231072876,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:268",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231072876,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291579712,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:268",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291579712,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276058940,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:268",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276058940,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585470336,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:268",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470336,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340352,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:268",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340352,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585659712,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:268",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659712,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tty_ldisc * tty_ldisc_ref_wait(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_ref_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585767824,
      "name": "tty_ldisc_ref_wait",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:268",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/selection.c:paste_selection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767824,
      "name": "tty_ldisc_ref_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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

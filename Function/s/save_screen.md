# Function: <code>save_screen</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584051280,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:641",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_bind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584051280,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584382112,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:635",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382112,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584564640,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:624",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564640,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584646272,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:624",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646272,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585058736,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:626",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058736,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585293248,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:626",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585293248,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585413296,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:930",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413296,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:930",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585627328,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585656835,
      "name": "save_screen.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585768528,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:931",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768528,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586499200,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:937",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586499200,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611376,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:943",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611376,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586495696,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:943",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586495696,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587027056,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027056,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588328576,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328576,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589748032,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589748032,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590052912,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:888",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590052912,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590392032,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:887",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590392032,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498485112,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:931",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498485112,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231139552,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:931",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231139552,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291673056,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:931",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291673056,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276117252,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:931",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276117252,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585529520,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:931",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529520,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585399344,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:931",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399344,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585718928,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:931",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718928,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void save_screen(struct vc_data * vc)
```

```json
{
  "name": "save_screen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585826960,
      "name": "save_screen",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:931",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826960,
      "name": "save_screen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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

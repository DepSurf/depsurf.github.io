# Function: <code>set_palette</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584053680,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:3995",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584053680,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584382384,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:3994",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382384,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584564912,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:3989",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564912,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584649632,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:3998",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584649632,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585062080,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4001",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062080,
      "name": "set_palette",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585296768,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:3999",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296768,
      "name": "set_palette",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585418528,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4313",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418528,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585632547,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4369",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585632512,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585656949,
      "name": "set_palette.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585772416,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4400",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772416,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586499280,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4410",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586499280,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611456,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4498",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611456,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586495776,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4498",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586495776,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587030192,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4503",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030192,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588331920,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4503",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331920,
      "name": "set_palette",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589752112,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4502",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589752112,
      "name": "set_palette",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590057296,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4450",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590057296,
      "name": "set_palette",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590396336,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4447",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590396336,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498489480,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4400",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498489480,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231143836,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4400",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231143836,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291679712,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4400",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291679712,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276121118,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4400",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276121118,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585533408,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4400",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533408,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585403232,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4400",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585403232,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585722816,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4400",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585722816,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void set_palette(struct vc_data * vc)
```

```json
{
  "name": "set_palette",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585830848,
      "name": "set_palette",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:4400",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_palette",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585830848,
      "name": "set_palette",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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

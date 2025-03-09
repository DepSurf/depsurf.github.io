# Function: <code>update_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583458128,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/console/bitblit.c:25",
      "file": "drivers/video/console/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/bitblit.c:bit_cursor",
        "drivers/video/console/bitblit.c:bit_putcs",
        "drivers/video/console/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071584053216,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:460",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583458128,
      "name": "update_attr.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071584053216,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583778384,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/console/bitblit.c:25",
      "file": "drivers/video/console/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/bitblit.c:bit_cursor",
        "drivers/video/console/bitblit.c:bit_putcs",
        "drivers/video/console/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071584384640,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:456",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583778384,
      "name": "update_attr.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071584384640,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583917696,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/console/bitblit.c:25",
      "file": "drivers/video/console/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/bitblit.c:bit_cursor",
        "drivers/video/console/bitblit.c:bit_putcs",
        "drivers/video/console/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071584567616,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:445",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917696,
      "name": "update_attr.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071584567616,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583966048,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/console/bitblit.c:25",
      "file": "drivers/video/console/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/bitblit.c:bit_cursor",
        "drivers/video/console/bitblit.c:bit_putcs",
        "drivers/video/console/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071584648992,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:445",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966048,
      "name": "update_attr.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071584648992,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584265312,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071585061424,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:447",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584265312,
      "name": "update_attr.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071585061424,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584485424,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071585295904,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:447",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485424,
      "name": "update_attr.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585295904,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584582192,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071585416320,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582192,
      "name": "update_attr.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585416320,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584780160,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071585631344,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780160,
      "name": "update_attr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585631344,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584915200,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071585772016,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915200,
      "name": "update_attr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585772016,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585609120,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071586497312,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:755",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:setterm_command",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:csi_m",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609120,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071586497312,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585740592,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071586609696,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:setterm_command",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:csi_m",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585740592,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071586609696,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585621264,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071586494064,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585621264,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071586494064,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586100096,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 0,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:745",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586100096,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071587029888,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071592449411,
      "name": "update_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587325808,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 0,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:745",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587325808,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071588331616,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071594317707,
      "name": "update_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588567600,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 0,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:745",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588567600,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071589751264,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071596235202,
      "name": "update_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588847728,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 0,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:694",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588847728,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071590056432,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071596763138,
      "name": "update_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void update_attr(struct eventfs_attr * attr, struct iattr * iattr)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585836864,
      "name": "update_attr",
      "external": false,
      "loc": "fs/tracefs/event_inode.c:110",
      "file": "fs/tracefs/event_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/tracefs/event_inode.c:eventfs_set_attr",
        "fs/tracefs/event_inode.c:eventfs_set_attr"
      ]
    },
    {
      "addr": 18446744071589150592,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 0,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:693",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585836864,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071589150592,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071590395472,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071597671766,
      "name": "update_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497312944,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446603336498489112,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497312944,
      "name": "update_attr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446603336498489112,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230489076,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 3231143484,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230489076,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3231143484,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291302704,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 13835058055291679264,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291302704,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 13835058055291679264,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275841038,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446743936276120762,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276120762,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446743936275841038,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584866064,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071585533008,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584866064,
      "name": "update_attr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585533008,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584795888,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071585402832,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584795888,
      "name": "update_attr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585402832,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584867488,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071585722416,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584867488,
      "name": "update_attr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585722416,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void update_attr(u8 * dst, u8 * src, int attribute, struct vc_data * vc)
```

```json
{
  "name": "update_attr",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584972864,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/video/fbdev/core/bitblit.c:25",
      "file": "drivers/video/fbdev/core/bitblit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs"
      ]
    },
    {
      "addr": 18446744071585830448,
      "name": "update_attr",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:749",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972864,
      "name": "update_attr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585830448,
      "name": "update_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct eventfs_attr * attr</code>
</li>
<li>
<b>Param added. </b>
<code>struct iattr * iattr</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 * dst</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 * src</code>
</li>
<li>
<b>Param removed. </b>
<code>int attribute</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vc_data * vc</code>
</li>
</ul>
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

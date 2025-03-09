# Function: <code>con_is_bound</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584050704,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3487",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_unregister_con_driver",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:set_con2fb_map",
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_event_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050704,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584381929,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3486",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_unregister_con_driver",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:set_con2fb_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381504,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584564457,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3485",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_unregister_con_driver",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:set_con2fb_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563776,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584647162,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3494",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:set_con2fb_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645616,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585060090,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3499",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058080,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585294547,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3497",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585292576,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585414947,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3812",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412624,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3852",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585656854,
      "name": "con_is_bound.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585627408,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585768608,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3883",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768608,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586499376,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3893",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_select_primary",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586499376,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611552,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3982",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_select_primary",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611552,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586495872,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3982",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586495872,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587027136,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3987",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027136,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588328672,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3987",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:do_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328672,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589748144,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3986",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:do_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589748144,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590053024,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3935",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:do_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590053024,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590392144,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3935",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:do_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590392144,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498485208,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3883",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498485208,
      "name": "con_is_bound",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231139672,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3883",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231139672,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291673216,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3883",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291673216,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276117332,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3883",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276117332,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585529600,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3883",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529600,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585399424,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3883",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399424,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585719008,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3883",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719008,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int con_is_bound(const struct consw * csw)
```

```json
{
  "name": "con_is_bound",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585827040,
      "name": "con_is_bound",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3883",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585827040,
      "name": "con_is_bound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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

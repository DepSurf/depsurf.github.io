# Function: <code>redraw_screen</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056016,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:664",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:set_con2fb_map",
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_bind_con_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056016,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584385440,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:658",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:set_con2fb_map",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385440,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584568320,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:647",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:set_con2fb_map",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584568320,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584649904,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:655",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:set_con2fb_map",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584649904,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585062368,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:657",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062368,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585297104,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:657",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297104,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585418816,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:964",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418816,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:964",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585656987,
      "name": "redraw_screen.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585633136,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585774416,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:976",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585774416,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586508064,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:982",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586508064,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586621088,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:988",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586621088,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586505328,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:988",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586505328,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587035184,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:984",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587035184,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588337376,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:984",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588337376,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589757920,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:984",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589757920,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590062784,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:933",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590062784,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590401952,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:932",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590401952,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498491944,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:976",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498491944,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231145744,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:976",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231145744,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291682160,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:976",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291682160,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276122780,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:976",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276122780,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585535408,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:976",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585535408,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585405232,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:976",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585405232,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585724816,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:976",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585724816,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void redraw_screen(struct vc_data * vc, int is_switch)
```

```json
{
  "name": "redraw_screen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585832848,
      "name": "redraw_screen",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:976",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resumed",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585832848,
      "name": "redraw_screen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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

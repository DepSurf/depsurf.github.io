# Function: <code>con_is_visible</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "con_is_visible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583745546,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:170",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_deinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583777025,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:170",
      "file": "drivers/video/console/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_set_palette",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_resize",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/video/console/fbcon.c:fb_flashcursor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584389034,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:170",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:scrdown",
        "drivers/tty/vt/vt.c:scrup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "con_is_visible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583885002,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:170",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_deinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583916337,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:170",
      "file": "drivers/video/console/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_set_palette",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_resize",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/video/console/fbcon.c:fb_flashcursor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584571866,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:170",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "con_is_visible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583933482,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:170",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_deinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583961699,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:170",
      "file": "drivers/video/console/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/fbcon.c:fbcon_event_notify",
        "drivers/video/console/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_set_palette",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_resize",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/video/console/fbcon.c:fb_flashcursor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584653448,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:170",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "con_is_visible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584196026,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:171",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_deinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584263961,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:171",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585064493,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:171",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "con_is_visible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584416695,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:171",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584480547,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:171",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585299151,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:171",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "con_is_visible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584511751,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:171",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584580413,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:171",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585419822,
      "name": "con_is_visible",
      "external": false,
      "loc": "include/linux/console_struct.h:171",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3875",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585656873,
      "name": "con_is_visible.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585627504,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585768688,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3906",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768688,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586499472,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3916",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_resize",
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_P",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:flush_scrollback",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586499472,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611648,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:4005",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_resize",
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_P",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:flush_scrollback",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611648,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586495968,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:4005",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586495968,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587045550,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:4010",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027248,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588347144,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:4010",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_resize",
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328800,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589766342,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:4009",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_resize",
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589748288,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590071222,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3958",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_resize",
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590053168,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590410390,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3958",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_resize",
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590392288,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498485352,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3906",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498485352,
      "name": "con_is_visible",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231139816,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3906",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231139816,
      "name": "con_is_visible",
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291673424,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3906",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291673424,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276117444,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3906",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276117444,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585529680,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3906",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529680,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585399504,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3906",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399504,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585719088,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3906",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719088,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool con_is_visible(const struct vc_data * vc)
```

```json
{
  "name": "con_is_visible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585827120,
      "name": "con_is_visible",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3906",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_set_palette",
        "drivers/video/console/vgacon.c:vgacon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585827120,
      "name": "con_is_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool con_is_visible(const struct vc_data * vc)
```
</details>
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

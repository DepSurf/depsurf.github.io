# Function: <code>is_console_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736880,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2186",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736880,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579757808,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2256",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757808,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783760,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2133",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783760,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579780416,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2102",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780416,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813872,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2090",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813872,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846080,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2251",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846080,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880912,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2254",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880912,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915456,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2309",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915456,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965504,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2319",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965504,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012256,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2339",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_start",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:flush_scrollback",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012256,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990448,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2423",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_start",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:flush_scrollback",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990448,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992208,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2492",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992208,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124064,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2553",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124064,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580265440,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2598",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:do_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_debug_leave",
        "drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_clear",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265440,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580471520,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2688",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:do_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_debug_leave",
        "drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_clear",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580471520,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543136,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2630",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:do_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_debug_leave",
        "drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_clear",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543136,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605024,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2667",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked",
        "drivers/video/fbdev/core/fbcon.c:do_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_debug_leave",
        "drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_resize",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_clear",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_register_con_driver",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:hide_cursor",
        "drivers/tty/vt/vt.c:add_softcursor",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605024,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491146536,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2319",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491146536,
      "name": "is_console_locked",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225175764,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2319",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225175764,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284041168,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2319",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284041168,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271704028,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2319",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271704028,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934240,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2319",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934240,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872512,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2319",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872512,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579925776,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2319",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925776,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int is_console_locked()
```

```json
{
  "name": "is_console_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971760,
      "name": "is_console_locked",
      "external": true,
      "loc": "kernel/printk/printk.c:2319",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_size",
        "drivers/tty/vt/vc_screen.c:vcs_vc",
        "drivers/tty/vt/vt.c:set_palette",
        "drivers/tty/vt/vt.c:poke_blanked_console",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/vt/vt.c:do_take_over_console",
        "drivers/tty/vt/vt.c:con_is_visible",
        "drivers/tty/vt/vt.c:con_is_bound",
        "drivers/tty/vt/vt.c:do_unbind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_allocate",
        "drivers/tty/vt/vt.c:redraw_screen",
        "drivers/tty/vt/vt.c:save_screen",
        "drivers/tty/vt/vt.c:set_origin",
        "drivers/tty/vt/vt.c:complement_pos",
        "drivers/tty/vt/vt.c:invert_screen",
        "drivers/tty/vt/vt.c:update_region",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971760,
      "name": "is_console_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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

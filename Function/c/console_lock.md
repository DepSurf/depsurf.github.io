# Function: <code>console_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724640,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2139",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_cpu_notify",
        "kernel/printk/printk.c:suspend_console",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_device",
        "fs/proc/consoles.c:c_start",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724640,
      "name": "console_lock",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579745696,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2209",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_cpu_notify",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745696,
      "name": "console_lock",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774400,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2086",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_cpu_notify",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774400,
      "name": "console_lock",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770544,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2055",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770544,
      "name": "console_lock",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803536,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2043",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803536,
      "name": "console_lock",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837008,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2217",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unbind_console",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837008,
      "name": "console_lock",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883936,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2220",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unbind_console",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883936,
      "name": "console_lock",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917536,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2275",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917536,
      "name": "console_lock",
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
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579967584,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2285",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967584,
      "name": "console_lock",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020517,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2305",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank"
      ],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_user",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014880,
      "name": "console_lock",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579998405,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2389",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank"
      ],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate",
        "drivers/tty/vt/vt_ioctl.c:vt_setactivate",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_user",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992960,
      "name": "console_lock",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580001349,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2458",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank"
      ],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994560,
      "name": "console_lock",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580134149,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2519",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank"
      ],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126016,
      "name": "console_lock",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580275624,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2564",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:__pr_flush",
        "kernel/printk/printk.c:__pr_flush",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank"
      ],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269632,
      "name": "console_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580485575,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2654",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "kernel/printk/printk.c:suspend_console"
      ],
      "caller_func": [
        "fs/proc/consoles.c:show_console_dev",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/kgdboc.c:configure_kgdboc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477040,
      "name": "console_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580557530,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2596",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "kernel/printk/printk.c:suspend_console"
      ],
      "caller_func": [
        "fs/proc/consoles.c:show_console_dev",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/kgdboc.c:configure_kgdboc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549072,
      "name": "console_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580626127,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2632",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank"
      ],
      "caller_func": [
        "fs/proc/consoles.c:show_console_dev",
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/kgdboc.c:configure_kgdboc",
        "drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_resume_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612096,
      "name": "console_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491148296,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2285",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/mx3fb.c:mx3fb_resume",
        "drivers/video/fbdev/mx3fb.c:mx3fb_suspend",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491148296,
      "name": "console_lock",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225178156,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2285",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/mx3fb.c:mx3fb_resume",
        "drivers/video/fbdev/mx3fb.c:mx3fb_suspend",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225178156,
      "name": "console_lock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284046112,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2285",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284046112,
      "name": "console_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271705988,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2285",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271705988,
      "name": "console_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579936320,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2285",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936320,
      "name": "console_lock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874592,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2285",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874592,
      "name": "console_lock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927856,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2285",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console",
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927856,
      "name": "console_lock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void console_lock()
```

```json
{
  "name": "console_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579986922,
      "name": "console_lock",
      "external": true,
      "loc": "kernel/printk/printk.c:2285",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:suspend_console"
      ],
      "caller_func": [
        "fs/proc/consoles.c:c_start",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:show_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973840,
      "name": "console_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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

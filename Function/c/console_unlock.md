# Function: <code>console_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579728384,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2234",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_cpu_notify",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_device",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/console/fbcon.c:fb_flashcursor",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
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
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/vt.c:give_up_console",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:con_driver_unregister_callback",
        "drivers/tty/vt/vt.c:vt_resize",
        "drivers/tty/vt/vt.c:con_init",
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
      "addr": 18446744071579728384,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1360
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748720,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2339",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_cpu_notify",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579748720,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1530
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775328,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2180",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_cpu_notify",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579775328,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1191
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772704,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2149",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_console_init",
        "drivers/video/console/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579772704,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1229
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805152,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2137",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579805152,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1237
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579838912,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2298",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unbind_console",
        "drivers/video/fbdev/core/fbmem.c:unbind_console",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579838912,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1219
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885568,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2302",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unbind_console",
        "drivers/video/fbdev/core/fbmem.c:unbind_console",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579885568,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1310
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920176,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2357",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579920176,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1235
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970240,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2367",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579970240,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1235
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019328,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2387",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
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
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate",
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
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
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
      "addr": 18446744071580019328,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1101
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579997392,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2471",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate",
        "drivers/tty/vt/vt_ioctl.c:vt_setactivate",
        "drivers/tty/vt/vt_ioctl.c:vt_setactivate",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
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
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
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
      "addr": 18446744071579997392,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 923
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000336,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2540",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
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
        "drivers/tty/vt/vt.c:con_font_get",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
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
      "addr": 18446744071580000336,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 913
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2601",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_virtual",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_rotate",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_bpp",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:store_mode",
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
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
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
        "drivers/tty/vt/vt.c:con_font_get",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
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
      "addr": 18446744071592133142,
      "name": "console_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071580133152,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 901
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2833",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__pr_flush",
        "kernel/printk/printk.c:__pr_flush",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
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
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
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
        "drivers/tty/vt/vt.c:con_font_get",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
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
      "addr": 18446744071593903982,
      "name": "console_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580275072,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2938",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
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
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
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
      "addr": 18446744071595985489,
      "name": "console_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580483648,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2979",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
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
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
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
      "addr": 18446744071596503759,
      "name": "console_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580555312,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:3013",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:vprintk_emit",
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
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered",
        "drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_clear_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_set_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:con_set_trans_old",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_get",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:do_con_write",
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
      "addr": 18446744071597401657,
      "name": "console_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580622672,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491155064,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2367",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
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
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/mx3fb.c:mx3fb_resume",
        "drivers/video/fbdev/mx3fb.c:mx3fb_suspend",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_font_op",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
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
      "addr": 18446603336491155064,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1484
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225182416,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2367",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
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
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/video/fbdev/mx3fb.c:mx3fb_resume",
        "drivers/video/fbdev/mx3fb.c:mx3fb_suspend",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_read",
        "drivers/tty/vt/vc_screen.c:vcs_lseek",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/vt/selection.c:set_selection_kernel",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
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
        "drivers/tty/vt/vt.c:con_font_op",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
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
      "addr": 3225182416,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1412
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284050784,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2367",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
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
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vc_screen.c:vcs_open",
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
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:store_bind",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_shutdown",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
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
      "addr": 13835058055284050784,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1860
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271708682,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2367",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
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
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:con_install",
        "drivers/tty/vt/vt.c:con_write",
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
      "addr": 18446743936271708682,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1478
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938976,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2367",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579938976,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1235
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877152,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2367",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579877152,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1201
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
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579930512,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2367",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579930512,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void console_unlock()
```

```json
{
  "name": "console_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579987085,
      "name": "console_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:2367",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:vprintk_emit",
        "fs/proc/consoles.c:c_stop",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_pan",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:show_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate_all",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:store_rotate",
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fbcon_remap_all",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor",
        "drivers/video/fbdev/core/fbcon.c:fb_console_init",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
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
      "addr": 18446744071579976368,
      "name": "console_unlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1203
    },
    {
      "addr": 18446744071579977584,
      "name": "console_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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

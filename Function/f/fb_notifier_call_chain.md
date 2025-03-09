# Function: <code>fb_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583481024,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_new_modelist",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583481024,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583801728,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_new_modelist",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583801728,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583940992,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_new_modelist",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940992,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583989136,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_new_modelist",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583989136,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204944,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_new_modelist",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204944,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584425296,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_new_modelist",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unbind_console",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425296,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584521680,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_new_modelist",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unbind_console",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584521680,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584720512,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720512,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584856704,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584856704,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585552800,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552800,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585687072,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687072,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585567776,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:50",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567776,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586039904,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:50",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039904,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587259952,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:50",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587259952,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588499680,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:50",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499680,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588778960,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:50",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588778960,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589082352,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:50",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082352,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497244120,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497244120,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230429440,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230429440,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291220704,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291220704,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275789272,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275789272,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584807888,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807888,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584738656,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584738656,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584809312,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584809312,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int fb_notifier_call_chain(long unsigned int val, void * v)
```

```json
{
  "name": "fb_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584914384,
      "name": "fb_notifier_call_chain",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_notify.c:43",
      "file": "drivers/video/fbdev/core/fb_notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_blank",
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914384,
      "name": "fb_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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

# Function: <code>lock_fb_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lock_fb_info(struct fb_info * info)
```

```json
{
  "name": "lock_fb_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583482448,
      "name": "lock_fb_info",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:77",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer"
      ],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583482448,
      "name": "lock_fb_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int lock_fb_info(struct fb_info * info)
```

```json
{
  "name": "lock_fb_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583809910,
      "name": "lock_fb_info",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:77",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802784,
      "name": "lock_fb_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int lock_fb_info(struct fb_info * info)
```

```json
{
  "name": "lock_fb_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583949174,
      "name": "lock_fb_info",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:77",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942048,
      "name": "lock_fb_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int lock_fb_info(struct fb_info * info)
```

```json
{
  "name": "lock_fb_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583995741,
      "name": "lock_fb_info",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:77",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990096,
      "name": "lock_fb_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int lock_fb_info(struct fb_info * info)
```

```json
{
  "name": "lock_fb_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584211613,
      "name": "lock_fb_info",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:79",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205904,
      "name": "lock_fb_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int lock_fb_info(struct fb_info * info)
```

```json
{
  "name": "lock_fb_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584431713,
      "name": "lock_fb_info",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:79",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unbind_console",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426208,
      "name": "lock_fb_info",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lock_fb_info(struct fb_info * info)
```

```json
{
  "name": "lock_fb_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584527944,
      "name": "lock_fb_info",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:83",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unbind_console",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522592,
      "name": "lock_fb_info",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584725799,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:639",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584741271,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:639",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584742207,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:639",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584862503,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584876055,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584876991,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585557711,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:633",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585573095,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:633",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585574031,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:633",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585691823,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:634",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585706583,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:634",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585707487,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:634",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585572127,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:634",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585586999,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:634",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585587904,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:634",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586046928,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:636",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586061799,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:636",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586063504,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:636",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587269315,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:645",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587282987,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:645",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587284989,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:645",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587301478,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:645",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_release"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588508691,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:640",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588522459,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:640",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588524573,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:640",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588542086,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:640",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_release"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588787379,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:620",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588800987,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:620",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588803101,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:620",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588821910,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:620",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_release"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589090219,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:605",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589109987,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:605",
      "file": "drivers/video/fbdev/core/fb_chrdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_chrdev.c:fb_release",
        "drivers/video/fbdev/core/fb_chrdev.c:fb_open",
        "drivers/video/fbdev/core/fb_chrdev.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116301,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:605",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes",
        "drivers/video/fbdev/core/fbsysfs.c:activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589124006,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:605",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497249792,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497271732,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497272676,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230433316,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3230449360,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3230450260,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291228536,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291250032,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291251280,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275794036,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275806270,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275807086,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584813687,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584827239,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584828175,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584744455,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584757767,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584758031,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584815111,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584828663,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584829599,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_fb_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584920183,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:fb_release",
        "drivers/video/fbdev/core/fbmem.c:fb_open",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584933735,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584934671,
      "name": "lock_fb_info",
      "external": false,
      "loc": "include/linux/fb.h:635",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbsysfs.c:store_fbstate",
        "drivers/video/fbdev/core/fbsysfs.c:store_modes"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int lock_fb_info(struct fb_info * info)
```
</details>
</li>
</ul>

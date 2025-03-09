# Function: <code>fbcon_fb_registered</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583455861,
      "name": "fbcon_fb_registered",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3145",
      "file": "drivers/video/console/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/console/fbcon.c:fbcon_event_notify"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583776051,
      "name": "fbcon_fb_registered",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3143",
      "file": "drivers/video/console/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/console/fbcon.c:fbcon_event_notify"
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
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583915363,
      "name": "fbcon_fb_registered",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3154",
      "file": "drivers/video/console/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/console/fbcon.c:fbcon_event_notify"
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
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583961237,
      "name": "fbcon_fb_registered",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3152",
      "file": "drivers/video/console/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/console/fbcon.c:fbcon_event_notify"
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
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584263499,
      "name": "fbcon_fb_registered",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3168",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify"
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
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584480134,
      "name": "fbcon_fb_registered",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3176",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify"
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
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584580527,
      "name": "fbcon_fb_registered",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3210",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_event_notify"
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
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3229",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779442,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071584777856,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3229",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914488,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071584912832,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2938",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609098,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585607264,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2895",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591424526,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585739296,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2887",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591365760,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071585619952,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2932",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396874,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071586097920,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3020",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594261999,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587323824,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3018",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596214362,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071588565520,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3011",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596739413,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071588845648,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3011",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_register_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597648269,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071589148512,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497310312,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3229",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497310312,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230487204,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3229",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230487204,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291300288,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3229",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291300288,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275839632,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3229",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275839632,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3229",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865360,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584863856,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3229",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584795184,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584793680,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3229",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584866784,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584865280,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int fbcon_fb_registered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_registered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_registered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3229",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972152,
      "name": "fbcon_fb_registered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071584970496,
      "name": "fbcon_fb_registered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int fbcon_fb_registered(struct fb_info * info)
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

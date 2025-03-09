# Function: <code>fbcon_fb_unregistered</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583455797,
      "name": "fbcon_fb_unregistered",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3062",
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
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583775983,
      "name": "fbcon_fb_unregistered",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3060",
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
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583915295,
      "name": "fbcon_fb_unregistered",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3071",
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
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583961079,
      "name": "fbcon_fb_unregistered",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3069",
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
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584263341,
      "name": "fbcon_fb_unregistered",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3085",
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
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584480283,
      "name": "fbcon_fb_unregistered",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3093",
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
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584579938,
      "name": "fbcon_fb_unregistered",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3114",
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3135",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779378,
      "name": "fbcon_fb_unregistered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584777520,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912416,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3135",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912416,
      "name": "fbcon_fb_unregistered",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585606848,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2844",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585606848,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738880,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2801",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738880,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585619536,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2793",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619536,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2838",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396787,
      "name": "fbcon_fb_unregistered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586097264,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2878",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594261912,
      "name": "fbcon_fb_unregistered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587323024,
      "name": "fbcon_fb_unregistered",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2876",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596214320,
      "name": "fbcon_fb_unregistered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588564640,
      "name": "fbcon_fb_unregistered",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2869",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596739371,
      "name": "fbcon_fb_unregistered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588844768,
      "name": "fbcon_fb_unregistered",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2869",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597648221,
      "name": "fbcon_fb_unregistered.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589147600,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497309744,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3135",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497309744,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230486604,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3135",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230486604,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291299408,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3135",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291299408,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275839104,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3135",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275839104,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584863520,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3135",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863520,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584793344,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3135",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584793344,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864944,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3135",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864944,
      "name": "fbcon_fb_unregistered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void fbcon_fb_unregistered(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unregistered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970080,
      "name": "fbcon_fb_unregistered",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3135",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970080,
      "name": "fbcon_fb_unregistered",
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
void fbcon_fb_unregistered(struct fb_info * info)
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

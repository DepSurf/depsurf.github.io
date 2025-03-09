# Function: <code>fbcon_fb_unbind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583456312,
      "name": "fbcon_fb_unbind",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3012",
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
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583776522,
      "name": "fbcon_fb_unbind",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3010",
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
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583915834,
      "name": "fbcon_fb_unbind",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3021",
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
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583960759,
      "name": "fbcon_fb_unbind",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3019",
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
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584263021,
      "name": "fbcon_fb_unbind",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3035",
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
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584480783,
      "name": "fbcon_fb_unbind",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3043",
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
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584580170,
      "name": "fbcon_fb_unbind",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3062",
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3084",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779359,
      "name": "fbcon_fb_unbind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584777120,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912016,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3084",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912016,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585606448,
      "name": "fbcon_fb_unbind",
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
      "addr": 18446744071585606448,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738480,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2750",
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
      "addr": 18446744071585738480,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585619136,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2742",
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
      "addr": 18446744071585619136,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586096352,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2787",
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
      "addr": 18446744071586096352,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587322160,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2829",
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
      "addr": 18446744071587322160,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 861
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563760,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2827",
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
      "addr": 18446744071588563760,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 861
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588843888,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2820",
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
      "addr": 18446744071588843888,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 861
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589146720,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2820",
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
      "addr": 18446744071589146720,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 861
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497309264,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3084",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497309264,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230486120,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3084",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230486120,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291298640,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3084",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291298640,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275838718,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3084",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275838718,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584863120,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3084",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863120,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584792944,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3084",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584792944,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864544,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3084",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864544,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void fbcon_fb_unbind(struct fb_info * info)
```

```json
{
  "name": "fbcon_fb_unbind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584969680,
      "name": "fbcon_fb_unbind",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3084",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969680,
      "name": "fbcon_fb_unbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void fbcon_fb_unbind(struct fb_info * info)
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

# Function: <code>fbcon_mode_deleted</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583455967,
      "name": "fbcon_mode_deleted",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2965",
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
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583776163,
      "name": "fbcon_mode_deleted",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2963",
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
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583915475,
      "name": "fbcon_mode_deleted",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2974",
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
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583961351,
      "name": "fbcon_mode_deleted",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2972",
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
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584263613,
      "name": "fbcon_mode_deleted",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2988",
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
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584480036,
      "name": "fbcon_mode_deleted",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2996",
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
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584579487,
      "name": "fbcon_mode_deleted",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3015",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776992,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3042",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776992,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584911888,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3042",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584911888,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585606320,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2751",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585606320,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738352,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2708",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738352,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585619008,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2700",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619008,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586096112,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2745",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586096112,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587321888,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2788",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587321888,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563472,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2786",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563472,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588843600,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2779",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588843600,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589146432,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2779",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589146432,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497309048,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3042",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497309048,
      "name": "fbcon_mode_deleted",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230485940,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3042",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230485940,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291298352,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3042",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291298352,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275838542,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3042",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275838542,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584862992,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3042",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584862992,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584792816,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3042",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584792816,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864416,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3042",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864416,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
```

```json
{
  "name": "fbcon_mode_deleted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584969552,
      "name": "fbcon_mode_deleted",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3042",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969552,
      "name": "fbcon_mode_deleted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int fbcon_mode_deleted(struct fb_info * info, struct fb_videomode * mode)
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

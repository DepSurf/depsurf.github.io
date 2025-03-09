# Function: <code>fbcon_fb_blanked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583456724,
      "name": "fbcon_fb_blanked",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3172",
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
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583776939,
      "name": "fbcon_fb_blanked",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3170",
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
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583916251,
      "name": "fbcon_fb_blanked",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3181",
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
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583961614,
      "name": "fbcon_fb_blanked",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3179",
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
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584263876,
      "name": "fbcon_fb_blanked",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3195",
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
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584480462,
      "name": "fbcon_fb_blanked",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3203",
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
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584580328,
      "name": "fbcon_fb_blanked",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3244",
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778096,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3263",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778096,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584913152,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3263",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913152,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607568,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2972",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607568,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585739600,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2929",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585739600,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585620272,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2921",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585620272,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586098400,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2966",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098400,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587323968,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3039",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323968,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588565680,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3037",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565680,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588845808,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3030",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588845808,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589148672,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3030",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589148672,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497310696,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3263",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497310696,
      "name": "fbcon_fb_blanked",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230487608,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3263",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230487608,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291300944,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3263",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291300944,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275839990,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3263",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275839990,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864096,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3263",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864096,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584793920,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3263",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584793920,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865520,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3263",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865520,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
```

```json
{
  "name": "fbcon_fb_blanked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970816,
      "name": "fbcon_fb_blanked",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3263",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbsysfs.c:store_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970816,
      "name": "fbcon_fb_blanked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void fbcon_fb_blanked(struct fb_info * info, int blank)
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

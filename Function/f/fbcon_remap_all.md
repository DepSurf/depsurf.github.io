# Function: <code>fbcon_remap_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583456203,
      "name": "fbcon_remap_all",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3100",
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
  "name": "fbcon_remap_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583776413,
      "name": "fbcon_remap_all",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3098",
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
  "name": "fbcon_remap_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583915725,
      "name": "fbcon_remap_all",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3109",
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
  "name": "fbcon_remap_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583960659,
      "name": "fbcon_remap_all",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3107",
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
  "name": "fbcon_remap_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584262921,
      "name": "fbcon_remap_all",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3123",
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
  "name": "fbcon_remap_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584479830,
      "name": "fbcon_remap_all",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3131",
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
  "name": "fbcon_remap_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584579664,
      "name": "fbcon_remap_all",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3155",
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3173",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779397,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071584777760,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3173",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914443,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071584912672,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2882",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609053,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585607104,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2839",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591424481,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585739136,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2831",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591365715,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585619792,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2876",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396808,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071586097728,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2922",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594261933,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587323600,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2920",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596214341,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588565232,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2913",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596739392,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588845360,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2913",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597648248,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589148224,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497310056,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3173",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497310056,
      "name": "fbcon_remap_all",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230486964,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3173",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230486964,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291299904,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3173",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291299904,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275839396,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3173",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275839396,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3173",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865315,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071584863760,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3173",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584795139,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071584793584,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3173",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584866739,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071584865184,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void fbcon_remap_all(struct fb_info * info)
```

```json
{
  "name": "fbcon_remap_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_remap_all",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3173",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972107,
      "name": "fbcon_remap_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071584970336,
      "name": "fbcon_remap_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void fbcon_remap_all(struct fb_info * info)
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

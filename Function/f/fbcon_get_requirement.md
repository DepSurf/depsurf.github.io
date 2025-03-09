# Function: <code>fbcon_get_requirement</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583456536,
      "name": "fbcon_get_requirement",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3215",
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
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583776748,
      "name": "fbcon_get_requirement",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3213",
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
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583916060,
      "name": "fbcon_get_requirement",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3224",
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
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583960915,
      "name": "fbcon_get_requirement",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:3222",
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
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584263177,
      "name": "fbcon_get_requirement",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3238",
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
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584480608,
      "name": "fbcon_get_requirement",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3246",
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
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584579756,
      "name": "fbcon_get_requirement",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:3287",
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778480,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3306",
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
      "addr": 18446744071584778480,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584913536,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3306",
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
      "addr": 18446744071584913536,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607952,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3015",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_check_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607952,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585739984,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2972",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_check_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585739984,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585620656,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2964",
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
      "addr": 18446744071585620656,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3009",
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
      "addr": 18446744071592397069,
      "name": "fbcon_get_requirement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071586099104,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3082",
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
      "addr": 18446744071594262047,
      "name": "fbcon_get_requirement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071587324784,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3080",
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
      "addr": 18446744071596214410,
      "name": "fbcon_get_requirement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071588566528,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3073",
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
      "addr": 18446744071596739461,
      "name": "fbcon_get_requirement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071588846656,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3073",
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
      "addr": 18446744071597648317,
      "name": "fbcon_get_requirement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071589149520,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497311184,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3306",
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
      "addr": 18446603336497311184,
      "name": "fbcon_get_requirement",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230488056,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3306",
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
      "addr": 3230488056,
      "name": "fbcon_get_requirement",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291301632,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3306",
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
      "addr": 13835058055291301632,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275840418,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3306",
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
      "addr": 18446743936275840418,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864480,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3306",
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
      "addr": 18446744071584864480,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584794304,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3306",
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
      "addr": 18446744071584794304,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865904,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3306",
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
      "addr": 18446744071584865904,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
```

```json
{
  "name": "fbcon_get_requirement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584971200,
      "name": "fbcon_get_requirement",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:3306",
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
      "addr": 18446744071584971200,
      "name": "fbcon_get_requirement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void fbcon_get_requirement(struct fb_info * info, struct fb_blit_caps * caps)
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

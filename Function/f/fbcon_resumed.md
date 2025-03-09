# Function: <code>fbcon_resumed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583456077,
      "name": "fbcon_resumed",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2878",
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
  "name": "fbcon_resumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583776287,
      "name": "fbcon_resumed",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2876",
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
  "name": "fbcon_resumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583915599,
      "name": "fbcon_resumed",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2887",
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
  "name": "fbcon_resumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583961474,
      "name": "fbcon_resumed",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2885",
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
  "name": "fbcon_resumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584263736,
      "name": "fbcon_resumed",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2901",
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
  "name": "fbcon_resumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584479976,
      "name": "fbcon_resumed",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2909",
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
  "name": "fbcon_resumed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584580477,
      "name": "fbcon_resumed",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2928",
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776928,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2945",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776928,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584911824,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2945",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584911824,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585606256,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2656",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585606256,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738288,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2613",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738288,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618944,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2605",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618944,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586096016,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2650",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586096016,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587321776,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2665",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587321776,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563344,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2663",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563344,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588843472,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2656",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588843472,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589146304,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2656",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589146304,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497308968,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2945",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497308968,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230485864,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2945",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230485864,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291298256,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2945",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291298256,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275838466,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2945",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275838466,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584862928,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2945",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584862928,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584792752,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2945",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584792752,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864352,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2945",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864352,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fbcon_resumed(struct fb_info * info)
```

```json
{
  "name": "fbcon_resumed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584969488,
      "name": "fbcon_resumed",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcon.c:2945",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_set_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969488,
      "name": "fbcon_resumed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fbcon_resumed(struct fb_info * info)
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

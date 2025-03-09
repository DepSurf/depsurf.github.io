# Function: <code>fb_prepare_logo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490528,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:674",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810864,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:674",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950128,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583989648,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:674",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583989648,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584205456,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:676",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205456,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584425808,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:677",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425808,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584522192,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:706",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522192,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584721024,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:698",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721024,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584857216,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:698",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584857216,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585553296,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:703",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585553296,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585687568,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:703",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687568,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585568272,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:703",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585568272,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586040176,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:703",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586040176,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587260272,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:701",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587260272,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588500048,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:703",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500048,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588779328,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:700",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588779328,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_prepare_logo",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_internal.h:30",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497244800,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:698",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497244800,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230429940,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:698",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230429940,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291221520,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:698",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291221520,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275789844,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:698",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275789844,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584808400,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:698",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584808400,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584739168,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:698",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739168,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584809824,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:698",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584809824,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int fb_prepare_logo(struct fb_info * info, int rotate)
```

```json
{
  "name": "fb_prepare_logo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584914896,
      "name": "fb_prepare_logo",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:698",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914896,
      "name": "fb_prepare_logo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int fb_prepare_logo(struct fb_info * info, int rotate)
```
</details>
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

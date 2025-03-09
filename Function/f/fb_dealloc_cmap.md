# Function: <code>fb_dealloc_cmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583500672,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:145",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583500672,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583821024,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:145",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583821024,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583960288,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:145",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960288,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008640,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:145",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008640,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224576,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:145",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224576,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584444912,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:145",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584444912,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584541568,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:145",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584541568,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584739472,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739472,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584874272,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584874272,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585573131,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp"
      ],
      "caller_func": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:init_asiliant",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571120,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585706619,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp"
      ],
      "caller_func": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:init_asiliant",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704608,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585587035,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp"
      ],
      "caller_func": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585585056,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586061835,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp"
      ],
      "caller_func": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059888,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587283023,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp"
      ],
      "caller_func": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587280960,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588522495,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp"
      ],
      "caller_func": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588520288,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588801023,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp"
      ],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588798864,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589090255,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp"
      ],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589088096,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497269048,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_remove",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_register",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/video/fbdev/mx3fb.c:mx3fb_remove",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497269048,
      "name": "fb_dealloc_cmap",
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230446928,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_remove",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/video/fbdev/mx3fb.c:mx3fb_remove",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230446928,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291247328,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/gxt4500.c:gxt4500_remove",
        "drivers/video/fbdev/gxt4500.c:gxt4500_probe",
        "drivers/video/fbdev/offb.c:offb_init_fb",
        "drivers/video/fbdev/offb.c:offb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291247328,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275804672,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275804672,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584825456,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584825456,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584755984,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584755984,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584826880,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584826880,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void fb_dealloc_cmap(struct fb_cmap * cmap)
```

```json
{
  "name": "fb_dealloc_cmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584931952,
      "name": "fb_dealloc_cmap",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbcmap.c:147",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/core/fbcmap.c:fb_alloc_cmap_gfp",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931952,
      "name": "fb_dealloc_cmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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

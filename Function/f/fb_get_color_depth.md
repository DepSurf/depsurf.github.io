# Function: <code>fb_get_color_depth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583481424,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:92",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:get_color",
        "drivers/video/console/fbcon.c:fbcon_set_palette",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/bitblit.c:bit_cursor",
        "drivers/video/console/bitblit.c:bit_putcs",
        "drivers/video/console/fbcon_cw.c:cw_cursor",
        "drivers/video/console/fbcon_cw.c:cw_putcs",
        "drivers/video/console/fbcon_ud.c:ud_cursor",
        "drivers/video/console/fbcon_ud.c:ud_putcs",
        "drivers/video/console/fbcon_ccw.c:ccw_cursor",
        "drivers/video/console/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583481424,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583801760,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:92",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_set_palette",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/video/console/fbcon.c:get_color",
        "drivers/video/console/bitblit.c:bit_cursor",
        "drivers/video/console/bitblit.c:bit_putcs",
        "drivers/video/console/fbcon_cw.c:cw_cursor",
        "drivers/video/console/fbcon_cw.c:cw_putcs",
        "drivers/video/console/fbcon_ud.c:ud_cursor",
        "drivers/video/console/fbcon_ud.c:ud_putcs",
        "drivers/video/console/fbcon_ccw.c:ccw_cursor",
        "drivers/video/console/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583801760,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583941024,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:92",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_set_palette",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/video/console/fbcon.c:get_color",
        "drivers/video/console/bitblit.c:bit_cursor",
        "drivers/video/console/bitblit.c:bit_putcs",
        "drivers/video/console/fbcon_cw.c:cw_cursor",
        "drivers/video/console/fbcon_cw.c:cw_putcs",
        "drivers/video/console/fbcon_ud.c:ud_cursor",
        "drivers/video/console/fbcon_ud.c:ud_putcs",
        "drivers/video/console/fbcon_ccw.c:ccw_cursor",
        "drivers/video/console/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583941024,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583996208,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:92",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_set_palette",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_prepare_logo",
        "drivers/video/console/fbcon.c:get_color",
        "drivers/video/console/bitblit.c:bit_cursor",
        "drivers/video/console/bitblit.c:bit_putcs",
        "drivers/video/console/fbcon_cw.c:cw_cursor",
        "drivers/video/console/fbcon_cw.c:cw_putcs",
        "drivers/video/console/fbcon_ud.c:ud_cursor",
        "drivers/video/console/fbcon_ud.c:ud_putcs",
        "drivers/video/console/fbcon_ccw.c:ccw_cursor",
        "drivers/video/console/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996208,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584212096,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:94",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212096,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584432176,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:94",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432176,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584528400,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:98",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528400,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584726256,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:87",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584726256,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584862960,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:87",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584862960,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585558928,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:88",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585558928,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585693040,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:88",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693040,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585573344,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:88",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585573344,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586044832,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:88",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044832,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587265504,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:90",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587265504,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588506432,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:92",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588506432,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588785616,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:89",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588785616,
      "name": "fb_get_color_depth",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589085952,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:66",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589085952,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497246960,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:87",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497246960,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230433708,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:87",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230433708,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291229296,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:87",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291229296,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275794460,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:87",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275794460,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584814144,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:87",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814144,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584744912,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:87",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744912,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584815568,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:87",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815568,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo * var, struct fb_fix_screeninfo * fix)
```

```json
{
  "name": "fb_get_color_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584920640,
      "name": "fb_get_color_depth",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:87",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_palette",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:get_color",
        "drivers/video/fbdev/core/bitblit.c:bit_cursor",
        "drivers/video/fbdev/core/bitblit.c:bit_putcs",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_cursor",
        "drivers/video/fbdev/core/fbcon_cw.c:cw_putcs",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_cursor",
        "drivers/video/fbdev/core/fbcon_ud.c:ud_putcs",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor",
        "drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920640,
      "name": "fb_get_color_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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

# Function: <code>mipi_dsi_dcs_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584344784,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:576",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344784,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585396640,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585396640,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585597552,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597552,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585681244,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680768,
      "name": "mipi_dsi_dcs_read",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586113468,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586112992,
      "name": "mipi_dsi_dcs_read",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586361292,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:736",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586360816,
      "name": "mipi_dsi_dcs_read",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586502540,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:738",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586502064,
      "name": "mipi_dsi_dcs_read",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586747724,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:738",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586747248,
      "name": "mipi_dsi_dcs_read",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586894156,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586893680,
      "name": "mipi_dsi_dcs_read",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587704092,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:786",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705376,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587764348,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:785",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765920,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587643628,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:785",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587645200,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588230188,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:785",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231760,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589616972,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:866",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589618832,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591217671,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:867",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness_large",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591219568,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591577063,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:867",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness_large",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591578976,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592304743,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:881",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness_large",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592306432,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499851928,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499851336,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232283904,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232282508,
      "name": "mipi_dsi_dcs_read",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293169308,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293167600,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276961726,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276960774,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586651244,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586650768,
      "name": "mipi_dsi_dcs_read",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586519740,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586519264,
      "name": "mipi_dsi_dcs_read",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586848716,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848240,
      "name": "mipi_dsi_dcs_read",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device * dsi, u8 cmd, void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586954828,
      "name": "mipi_dsi_dcs_read",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:733",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954352,
      "name": "mipi_dsi_dcs_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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

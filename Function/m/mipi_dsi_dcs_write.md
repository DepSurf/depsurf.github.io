# Function: <code>mipi_dsi_dcs_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584343664,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:536",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584343664,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585396566,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585395520,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585597478,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585596336,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585680694,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679584,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586112918,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111808,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586360777,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:696",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586359616,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586502025,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:698",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586500864,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586747209,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:698",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586747856,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586893641,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586894288,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587705909,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:746",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703200,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587766268,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:745",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587763328,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587645548,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:745",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587642640,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588232108,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:745",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588229200,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589617858,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:826",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589615408,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591219122,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:827",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness_large",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591215376,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591578530,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:827",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness_large",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591574672,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592305826,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:841",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness_large",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592302160,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499851292,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499849824,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232283656,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232285736,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293169000,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293171776,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276961572,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276963078,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586650729,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651376,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586519225,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586519872,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586848201,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848848,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device * dsi, u8 cmd, const void * data, size_t len)
```

```json
{
  "name": "mipi_dsi_dcs_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586954313,
      "name": "mipi_dsi_dcs_write",
      "external": true,
      "loc": "drivers/gpu/drm/drm_mipi_dsi.c:693",
      "file": "drivers/gpu/drm/drm_mipi_dsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954960,
      "name": "mipi_dsi_dcs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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

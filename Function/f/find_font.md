# Function: <code>find_font</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583149472,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:90",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_set_def_font",
        "drivers/video/console/fbcon.c:fbcon_startup",
        "drivers/video/console/fbcon.c:fbcon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149472,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444752,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:90",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_set_def_font",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444752,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570496,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:90",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_set_def_font",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570496,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583608016,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:90",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_set_def_font",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583608016,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854048,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:90",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854048,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584054352,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:90",
      "file": "lib/fonts/fonts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584054352,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137472,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:94",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137472,
      "name": "find_font",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584327760,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584327760,
      "name": "find_font",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584462448,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462448,
      "name": "find_font",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585026272,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585026272,
      "name": "find_font",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585174992,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:82",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585174992,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585056720,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:82",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585056720,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585501344,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:82",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585501344,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586649408,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:82",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586649408,
      "name": "find_font",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587893632,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:82",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587893632,
      "name": "find_font",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588165344,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:82",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588165344,
      "name": "find_font",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588456048,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:82",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456048,
      "name": "find_font",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496351904,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496351904,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229684564,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229684564,
      "name": "find_font",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290675536,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290675536,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275398114,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275398114,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584431184,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584431184,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584366288,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584366288,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584414096,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584414096,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
const struct font_desc * find_font(const char * name)
```

```json
{
  "name": "find_font",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584520160,
      "name": "find_font",
      "external": true,
      "loc": "lib/fonts/fonts.c:79",
      "file": "lib/fonts/fonts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520160,
      "name": "find_font",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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

# Function: <code>backlight_device_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583478432,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:407",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583478432,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583798768,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:416",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583798768,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583938048,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:416",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938048,
      "name": "backlight_device_unregister",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583986776,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:421",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986576,
      "name": "backlight_device_unregister.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071583986736,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584202584,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:421",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202384,
      "name": "backlight_device_unregister.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071584202544,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584422920,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:421",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422720,
      "name": "backlight_device_unregister.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071584422880,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584519320,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:421",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584519120,
      "name": "backlight_device_unregister.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071584519280,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584718120,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:422",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584717920,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071584718080,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584854232,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:441",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584854016,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584854192,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585550232,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:462",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585550016,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071585550192,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585684520,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:508",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585684304,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071585684480,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585565224,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:508",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585565008,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071585565184,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586037080,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:508",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586036864,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071586037040,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587256936,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:520",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587256704,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071587256880,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588496456,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:520",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496192,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071588496384,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588776200,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:520",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588775936,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071588776128,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589079544,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:520",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589079280,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071589079472,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497242052,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:441",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release",
        "drivers/video/fbdev/mx3fb.c:mx3fb_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497241816,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336497241976,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230427496,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:441",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release",
        "drivers/video/fbdev/mx3fb.c:mx3fb_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230427296,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 3230427436,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291216692,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:441",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291216384,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 13835058055291216640,
      "name": "backlight_device_unregister",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584805416,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:441",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584805200,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584805376,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584736184,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:441",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735968,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584736144,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584806840,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:441",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584806624,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584806800,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```

```json
{
  "name": "backlight_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584911912,
      "name": "backlight_device_unregister",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:441",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ],
      "caller_func": [
        "drivers/video/backlight/backlight.c:devm_backlight_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584911696,
      "name": "backlight_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584911872,
      "name": "backlight_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void backlight_device_unregister(struct backlight_device * bd)
```
</details>
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

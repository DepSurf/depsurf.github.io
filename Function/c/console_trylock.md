# Function: <code>console_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579726192,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2159",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:console_flush_on_panic",
        "drivers/video/console/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726192,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579746592,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2229",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/console/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746592,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579775072,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2106",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/console/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775072,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579773410,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2075",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/console/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772528,
      "name": "console_trylock.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579772672,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579805822,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2063",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804752,
      "name": "console_trylock.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579805120,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579839704,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2237",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837952,
      "name": "console_trylock.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579838096,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579886373,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2240",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884608,
      "name": "console_trylock.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579884752,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579920993,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2295",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919216,
      "name": "console_trylock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579919360,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579971057,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2305",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969280,
      "name": "console_trylock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579969424,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580018928,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2325",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_trylock_spinning",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018928,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579996992,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2409",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_trylock_spinning",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579996992,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580000144,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2478",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000144,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580132960,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2539",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132960,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580283461,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2584",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_trylock_spinning"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270624,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580492677,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2674",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_trylock_spinning"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478096,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580564517,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2616",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_trylock_spinning"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580550496,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580622807,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2654",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_trylock_spinning"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611968,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491155980,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2305",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491150424,
      "name": "console_trylock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336491150600,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225179588,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2305",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225179588,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284052012,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2305",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284048464,
      "name": "console_trylock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 13835058055284048576,
      "name": "console_trylock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271709732,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2305",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271707292,
      "name": "console_trylock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446743936271707366,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939793,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2305",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938016,
      "name": "console_trylock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579938160,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579877942,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2305",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579875088,
      "name": "console_trylock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579875152,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579931329,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2305",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929552,
      "name": "console_trylock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579929696,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int console_trylock()
```

```json
{
  "name": "console_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985180,
      "name": "console_trylock",
      "external": true,
      "loc": "kernel/printk/printk.c:2305",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:vprintk_emit",
        "drivers/video/fbdev/core/fbcon.c:fb_flashcursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579976192,
      "name": "console_trylock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579976336,
      "name": "console_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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

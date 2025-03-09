# Function: <code>fbcon_putcs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583433536,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:1275",
      "file": "drivers/video/console/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_putc",
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_scrolldelta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583433536,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583752752,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:1274",
      "file": "drivers/video/console/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752752,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892256,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:1277",
      "file": "drivers/video/console/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892256,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583950800,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:1275",
      "file": "drivers/video/console/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_scrolldelta",
        "drivers/video/console/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950800,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584246528,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1291",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584246528,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584466864,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1298",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466864,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584556784,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1317",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556784,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584754656,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1345",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754656,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584889440,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1345",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584889440,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585586976,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1300",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585586976,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585719504,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1296",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719504,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585599952,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1288",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585599952,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586085264,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1288",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085264,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587307904,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1279",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587307904,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588549088,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1274",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588549088,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588829136,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1273",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_redraw",
        "drivers/video/fbdev/core/fbcon.c:fbcon_redraw",
        "drivers/video/fbdev/core/fbcon.c:fbcon_redraw",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588829136,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589132016,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1275",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_redraw",
        "drivers/video/fbdev/core/fbcon.c:fbcon_redraw",
        "drivers/video/fbdev/core/fbcon.c:fbcon_redraw",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132016,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497292952,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1345",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497292952,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230464420,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1345",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230464420,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291269696,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1345",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291269696,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275818636,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1345",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275818636,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584840624,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1345",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584840624,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584770448,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1345",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584770448,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584842048,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1345",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584842048,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void fbcon_putcs(struct vc_data * vc, const short unsigned int * s, int count, int ypos, int xpos)
```

```json
{
  "name": "fbcon_putcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584947104,
      "name": "fbcon_putcs",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1345",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta",
        "drivers/video/fbdev/core/fbcon.c:fbcon_putc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947104,
      "name": "fbcon_putcs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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

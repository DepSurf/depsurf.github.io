# Function: <code>__do_SAK</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583970864,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3043",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970864,
      "name": "__do_SAK",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584303392,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3056",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584303392,
      "name": "__do_SAK",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584485456,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3056",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485456,
      "name": "__do_SAK",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584564565,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2603",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564064,
      "name": "__do_SAK.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071584566848,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584970453,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2710",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969952,
      "name": "__do_SAK.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071584978480,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585204853,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2728",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204592,
      "name": "__do_SAK.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071585214732,
      "name": "__do_SAK.part.29.cold.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071585211840,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585322933,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2883",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585322672,
      "name": "__do_SAK.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071585333676,
      "name": "__do_SAK.part.28.cold.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071585330784,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585534949,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2887",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585534672,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071585546417,
      "name": "__do_SAK.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    },
    {
      "addr": 18446744071585543456,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585675829,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2889",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675552,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071585687329,
      "name": "__do_SAK.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071585684368,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586402917,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2892",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586402640,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071586415839,
      "name": "__do_SAK.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071586412016,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586520453,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2980",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586520016,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    },
    {
      "addr": 18446744071591457850,
      "name": "__do_SAK.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071586527664,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586404821,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3029",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404384,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071591399520,
      "name": "__do_SAK.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071586412624,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586931605,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3029",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586931168,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071592445949,
      "name": "__do_SAK.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071586939616,
      "name": "__do_SAK",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3002",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594314421,
      "name": "__do_SAK.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071588233408,
      "name": "__do_SAK",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589644176,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3001",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589644176,
      "name": "__do_SAK",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589948032,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3010",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589948032,
      "name": "__do_SAK",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590286448,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3027",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590286448,
      "name": "__do_SAK",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 855
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498348880,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2889",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498348168,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
    },
    {
      "addr": 18446603336498361848,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231042308,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2889",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231041704,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    },
    {
      "addr": 3231047532,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291537552,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2889",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291536768,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
    },
    {
      "addr": 13835058055291545984,
      "name": "__do_SAK",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276031248,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2889",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276030702,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 18446743936276037304,
      "name": "__do_SAK",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585436853,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2889",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436576,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071585448353,
      "name": "__do_SAK.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071585445392,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585306901,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2889",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306624,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071585318385,
      "name": "__do_SAK.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071585315424,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585626229,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2889",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585625952,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071585637729,
      "name": "__do_SAK.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071585634768,
      "name": "__do_SAK",
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
void __do_SAK(struct tty_struct * tty)
```

```json
{
  "name": "__do_SAK",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585733525,
      "name": "__do_SAK",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2889",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:do_SAK_work"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:do_SAK_work",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585733264,
      "name": "__do_SAK.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071585745898,
      "name": "__do_SAK.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071585742896,
      "name": "__do_SAK",
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

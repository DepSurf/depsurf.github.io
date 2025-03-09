# Function: <code>wakeup_source_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465216,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465216,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584801600,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584801600,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584993600,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584993600,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585079456,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:155",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585079072,
      "name": "wakeup_source_destroy.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071585079280,
      "name": "wakeup_source_destroy",
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585502800,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:155",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585502416,
      "name": "wakeup_source_destroy.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071585502624,
      "name": "wakeup_source_destroy",
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585747584,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:160",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585746144,
      "name": "wakeup_source_destroy.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071585746352,
      "name": "wakeup_source_destroy",
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585880304,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:159",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585878928,
      "name": "wakeup_source_destroy.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071585879120,
      "name": "wakeup_source_destroy",
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586117393,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:143",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115360,
      "name": "wakeup_source_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071586115568,
      "name": "wakeup_source_destroy",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586263360,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263360,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587032518,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:156",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032688,
      "name": "wakeup_source_destroy",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587115974,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:156",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116144,
      "name": "wakeup_source_destroy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587002246,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:156",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002416,
      "name": "wakeup_source_destroy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587568422,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:157",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568592,
      "name": "wakeup_source_destroy",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588903348,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:157",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588903696,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590414708,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:157",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590415120,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590734228,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:152",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590734640,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591096196,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:152",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591096608,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499085808,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499085808,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231638108,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231638108,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292266496,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292266496,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586026688,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586026688,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585872640,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585872640,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213376,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213376,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void wakeup_source_destroy(struct wakeup_source * ws)
```

```json
{
  "name": "wakeup_source_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586322480,
      "name": "wakeup_source_destroy",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:153",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586322480,
      "name": "wakeup_source_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void wakeup_source_destroy(struct wakeup_source * ws)
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

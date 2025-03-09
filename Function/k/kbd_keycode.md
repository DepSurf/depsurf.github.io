# Function: <code>kbd_keycode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584037210,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1327",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584367978,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1315",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584549802,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1315",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584632291,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1315",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585044707,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1316",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585278648,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1316",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585398612,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1346",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1347",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585612576,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2745
    },
    {
      "addr": 18446744071585621027,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1347",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753728,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2745
    },
    {
      "addr": 18446744071585762243,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1353",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586482992,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1583
    },
    {
      "addr": 18446744071586492211,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1375",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586596944,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1613
    },
    {
      "addr": 18446744071591459107,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1385",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586480656,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1505
    },
    {
      "addr": 18446744071591400797,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1385",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010368,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1786
    },
    {
      "addr": 18446744071592449084,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void kbd_keycode(unsigned int keycode, int down, bool hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1397",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588310208,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1864
    },
    {
      "addr": 18446744071594317334,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1397",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589729072,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1366
    },
    {
      "addr": 18446744071596234860,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1397",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590033904,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1482
    },
    {
      "addr": 18446744071596762807,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1397",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590372752,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1482
    },
    {
      "addr": 18446744071597671389,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498461648,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1347",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498461648,
      "name": "kbd_keycode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1500
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
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231122876,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1347",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231122876,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2740
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
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291649808,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1347",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291649808,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276103444,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1347",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276103444,
      "name": "kbd_keycode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1314
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1347",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514720,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2745
    },
    {
      "addr": 18446744071585523235,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1347",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585384544,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2745
    },
    {
      "addr": 18446744071585393059,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1347",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704128,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2745
    },
    {
      "addr": 18446744071585712643,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```

```json
{
  "name": "kbd_keycode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kbd_keycode",
      "external": false,
      "loc": "drivers/tty/vt/keyboard.c:1347",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585812160,
      "name": "kbd_keycode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2745
    },
    {
      "addr": 18446744071585820675,
      "name": "kbd_keycode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int hw_raw</code> ➡️ <code>bool hw_raw</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
```
</details>
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
void kbd_keycode(unsigned int keycode, int down, int hw_raw)
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

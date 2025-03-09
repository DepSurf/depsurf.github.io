# Function: <code>i8042_controller_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i8042_controller_resume(bool force_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585552272,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1113",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552272,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int i8042_controller_resume(bool force_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585946112,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1113",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946112,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586134560,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1145",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586134560,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586223472,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1153",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586223472,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586686752,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1153",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686752,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1153",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951184,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071586953669,
      "name": "i8042_controller_resume.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1156",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112064,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071587114528,
      "name": "i8042_controller_resume.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1149",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376656,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071587379200,
      "name": "i8042_controller_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1166",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578544,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071587581116,
      "name": "i8042_controller_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588441013,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1168",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_restore"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588440480,
      "name": "i8042_controller_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 18446744071588442506,
      "name": "i8042_controller_resume.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071588440816,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588442642,
      "name": "i8042_controller_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588472613,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1191",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_restore"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472080,
      "name": "i8042_controller_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 18446744071591571619,
      "name": "i8042_controller_resume.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071588472416,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071591571755,
      "name": "i8042_controller_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588354381,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1191",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588354304,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071591514572,
      "name": "i8042_controller_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589016405,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1195",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_restore"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589015776,
      "name": "i8042_controller_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071592619243,
      "name": "i8042_controller_resume.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071589016160,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071592619446,
      "name": "i8042_controller_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590454421,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1195",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_restore"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590453472,
      "name": "i8042_controller_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071594502597,
      "name": "i8042_controller_resume.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071590454160,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071594502898,
      "name": "i8042_controller_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592095573,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1195",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_restore"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592094528,
      "name": "i8042_controller_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    },
    {
      "addr": 18446744071596303410,
      "name": "i8042_controller_resume.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071592095264,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592519189,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1195",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_restore"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592518144,
      "name": "i8042_controller_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    },
    {
      "addr": 18446744071596832825,
      "name": "i8042_controller_resume.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071592518880,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593263781,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1195",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_restore"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593262736,
      "name": "i8042_controller_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    },
    {
      "addr": 18446744071597756858,
      "name": "i8042_controller_resume.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071593263472,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294165168,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1166",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294165168,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587271285,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1166",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_restore"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1166",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039856,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071587042412,
      "name": "i8042_controller_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1166",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587529792,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071587532364,
      "name": "i8042_controller_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int i8042_controller_resume(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_resume",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1166",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587641024,
      "name": "i8042_controller_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071587643500,
      "name": "i8042_controller_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool s2r_wants_reset</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force_reset</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset)
```
</details>
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

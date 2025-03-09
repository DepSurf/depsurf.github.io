# Function: <code>i8042_controller_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void i8042_controller_reset(bool force_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585552736,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1022",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/serio/i8042.c:i8042_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552736,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void i8042_controller_reset(bool force_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585946592,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1022",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946592,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586135040,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1052",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586135040,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586223040,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1060",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586223040,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586686320,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1060",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686320,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1060",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950528,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071586953553,
      "name": "i8042_controller_reset.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1063",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587111408,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071587114412,
      "name": "i8042_controller_reset.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1056",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376256,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071587379166,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1073",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578144,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071587581082,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1075",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588438880,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071588442431,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1098",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588470496,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071591571462,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1098",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588352720,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071591514415,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1102",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589013936,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071592619045,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1102",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590452288,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071594502310,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1102",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592093696,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071596303350,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1102",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592517312,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071596832765,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1102",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593261904,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071597756798,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294162496,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1073",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294162496,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1073",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587271504,
      "name": "i8042_controller_reset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071587274008,
      "name": "i8042_controller_reset.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1073",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039456,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071587042378,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1073",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587529392,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071587532330,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```

```json
{
  "name": "i8042_controller_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_controller_reset",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:1073",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_remove",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_shutdown",
        "drivers/input/serio/i8042.c:i8042_pm_reset",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587640624,
      "name": "i8042_controller_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071587643466,
      "name": "i8042_controller_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void i8042_controller_reset(bool s2r_wants_reset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset)
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
void i8042_controller_reset(bool s2r_wants_reset)
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
void i8042_controller_reset(bool s2r_wants_reset)
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

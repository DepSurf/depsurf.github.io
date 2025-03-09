# Function: <code>i8042_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585548896,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:235",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_controller_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585548896,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585942640,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:235",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942640,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586131088,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:265",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586131088,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586219456,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:265",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586219456,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586682800,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:265",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586682800,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:265",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948272,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071586952716,
      "name": "i8042_flush.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:265",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587109072,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071587113596,
      "name": "i8042_flush.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:261",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373520,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071587378170,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:261",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587575360,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071587580090,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:263",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588436032,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071588441091,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:283",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588467616,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071591570125,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:283",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588349952,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071591513423,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:287",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589009168,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071592616912,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:287",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590445856,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071594499997,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:287",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592085968,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071596302166,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:287",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592508704,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071596831583,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:287",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593253200,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071597755616,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294157936,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:261",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294157936,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:261",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587268384,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071587272906,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:261",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036672,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071587041386,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:261",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587526608,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071587531338,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int i8042_flush()
```

```json
{
  "name": "i8042_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_flush",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:261",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637776,
      "name": "i8042_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071587642474,
      "name": "i8042_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int i8042_flush()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int i8042_flush()
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
int i8042_flush()
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

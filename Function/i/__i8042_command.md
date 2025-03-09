# Function: <code>__i8042_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585550496,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:269",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585550496,
      "name": "__i8042_command.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585944946,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:269",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585944288,
      "name": "__i8042_command.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586133394,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:299",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586132736,
      "name": "__i8042_command.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586221874,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:299",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221008,
      "name": "__i8042_command.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586685154,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:299",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684352,
      "name": "__i8042_command.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int __i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:299",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949376,
      "name": "__i8042_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    },
    {
      "addr": 18446744071586953209,
      "name": "__i8042_command.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int __i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587110330,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:299",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587110256,
      "name": "__i8042_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    },
    {
      "addr": 18446744071587114068,
      "name": "__i8042_command.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605083623,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:295",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587374624,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071587378650,
      "name": "__i8042_command.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605123106,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:295",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587576464,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071587580570,
      "name": "__i8042_command.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609399988,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:297",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588437520,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071588441667,
      "name": "__i8042_command.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612472072,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:317",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588469104,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071591570701,
      "name": "__i8042_command.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614614214,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:317",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588351328,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071591513999,
      "name": "__i8042_command.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589016962,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:321",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589011952,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071592618294,
      "name": "__i8042_command.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
int __i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:321",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590448704,
      "name": "__i8042_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
    },
    {
      "addr": 18446744071594501428,
      "name": "__i8042_command.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:321",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592089536,
      "name": "__i8042_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071596302916,
      "name": "__i8042_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int __i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:321",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592512480,
      "name": "__i8042_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071596832331,
      "name": "__i8042_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int __i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:321",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593257072,
      "name": "__i8042_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071597756364,
      "name": "__i8042_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302820880,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:295",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294159776,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
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
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605020097,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:295",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587269680,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071587273386,
      "name": "__i8042_command.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604984360,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:295",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037776,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071587041866,
      "name": "__i8042_command.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605101497,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:295",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587527712,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071587531818,
      "name": "__i8042_command.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__i8042_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605127300,
      "name": "__i8042_command",
      "external": false,
      "loc": "drivers/input/serio/i8042.c:295",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639072,
      "name": "__i8042_command.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071587642954,
      "name": "__i8042_command.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int __i8042_command(unsigned char * param, int command)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int __i8042_command(unsigned char * param, int command)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int __i8042_command(unsigned char * param, int command)
```
</details>
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

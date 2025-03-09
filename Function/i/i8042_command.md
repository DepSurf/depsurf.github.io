# Function: <code>i8042_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585551088,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:311",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551088,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585944912,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:311",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585944912,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586133360,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:341",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586133360,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586221840,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:343",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221840,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586685120,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:343",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586685120,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586949744,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:343",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949744,
      "name": "i8042_command",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587110624,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:343",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587110624,
      "name": "i8042_command",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587375200,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375200,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587577072,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587577072,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588437888,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:341",
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
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588437888,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588469472,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:361",
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
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588469472,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588351696,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:361",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588351696,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:365",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_init",
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
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592618617,
      "name": "i8042_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589012400,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590452336,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:365",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_init",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
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
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594501761,
      "name": "i8042_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590449248,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592097466,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:365",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596303056,
      "name": "i8042_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592090272,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592521082,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:365",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596832471,
      "name": "i8042_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592513216,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593265674,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:365",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597756504,
      "name": "i8042_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593257808,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294161088,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_aux_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294161088,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587270208,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_pm_restore",
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587270208,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587038384,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587038384,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587528320,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587528320,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int i8042_command(unsigned char * param, int command)
```

```json
{
  "name": "i8042_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639552,
      "name": "i8042_command",
      "external": true,
      "loc": "drivers/input/serio/i8042.c:339",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_controller_resume",
        "drivers/input/serio/i8042.c:i8042_dritek_enable",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_reset",
        "drivers/input/serio/i8042.c:i8042_controller_selftest",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_set_mux_mode",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_enable_mux_ports",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_aux_write",
        "drivers/input/serio/i8042.c:i8042_platform_init",
        "drivers/input/serio/i8042.c:i8042_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639552,
      "name": "i8042_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int i8042_command(unsigned char * param, int command)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int i8042_command(unsigned char * param, int command)
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
int i8042_command(unsigned char * param, int command)
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

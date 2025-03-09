# Function: <code>ps2_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ps2_command(struct ps2dev * ps2dev, unsigned char * param, int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585556576,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:261",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585556576,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int ps2_command(struct ps2dev * ps2dev, unsigned char * param, int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585950448,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:259",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950448,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, unsigned char * param, int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586138864,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:259",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586138864,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, unsigned char * param, int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586227808,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:259",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586227808,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, unsigned char * param, int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586691088,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:259",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691088,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586957232,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:331",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957232,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587118096,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:331",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587118096,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587382736,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382736,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587584672,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587584672,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588446144,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_reconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588446144,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588476112,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_reconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588476112,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588358224,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_reconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588358224,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589021856,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_reconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589021856,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590459968,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_reconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590459968,
      "name": "ps2_command",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592102336,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:330",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_reconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592102336,
      "name": "ps2_command",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592526064,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:401",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_reconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592526064,
      "name": "ps2_command",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593270656,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:401",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_reconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593270656,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500725976,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500725976,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233248180,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233248180,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294170880,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294170880,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277571688,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277571688,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587277488,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587277488,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587045920,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587045920,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587535920,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587535920,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ps2_command(struct ps2dev * ps2dev, u8 * param, unsigned int command)
```

```json
{
  "name": "ps2_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587646240,
      "name": "ps2_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:327",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_reset_state",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_select_set",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_probe",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_leds",
        "drivers/input/keyboard/atkbd.c:atkbd_set_repeat_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646240,
      "name": "ps2_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char * param</code> ➡️ <code>u8 * param</code>
</li>
<li>
<b>Param type changed. </b>
<code>int command</code> ➡️ <code>unsigned int command</code>
</li>
</ul>
</details>
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

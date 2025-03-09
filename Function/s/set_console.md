# Function: <code>set_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584064992,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2486",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064992,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584395824,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2485",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395824,
      "name": "set_console",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584578144,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2484",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578144,
      "name": "set_console",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584659808,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2493",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659808,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072128,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2497",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072128,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585306816,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2495",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306816,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585428864,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2827",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585428864,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585643536,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2862",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585643536,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585784880,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2886",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585784880,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586517680,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2895",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:setterm_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586517680,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586630912,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2984",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_setactivate",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:setterm_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630912,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586515088,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2984",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586515088,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3013",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592449916,
      "name": "set_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587049968,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3013",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594318238,
      "name": "set_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588352480,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:3013",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596235420,
      "name": "set_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589773568,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2967",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596763356,
      "name": "set_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590078496,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2966",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597671984,
      "name": "set_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590417664,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498502680,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2886",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498502680,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231156732,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2886",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231156732,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291697040,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2886",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291697040,
      "name": "set_console",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276132560,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2886",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276132560,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585545872,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2886",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545872,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585415696,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2886",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585415696,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585735280,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2886",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585735280,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int set_console(int nr)
```

```json
{
  "name": "set_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585843296,
      "name": "set_console",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:2886",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_move_to_console",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:k_cons",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_lastcons",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843296,
      "name": "set_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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

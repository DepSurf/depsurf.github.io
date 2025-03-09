# Function: <code>gotoxy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584050384,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1069",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:putconsxy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050384,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584380944,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1075",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584380944,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584563216,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1069",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563216,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584645056,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1077",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645056,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585057488,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1079",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585057488,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585291584,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1079",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585291584,
      "name": "gotoxy",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585411632,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1401",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585411632,
      "name": "gotoxy",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585625840,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1410",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585625840,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585767040,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1434",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767040,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586528734,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1447",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:putconsxy"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586497488,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586640478,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1446",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:putconsxy"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586609856,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586524494,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1446",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:putconsxy"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586494224,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587062014,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1452",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:putconsxy"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025296,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588364504,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1452",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:putconsxy"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588326656,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589785912,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1452",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:putconsxy"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589745904,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590090984,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1407",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:putconsxy"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590050752,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590430232,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1406",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:putconsxy"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590389872,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498483112,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1434",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498483112,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231137928,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1434",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231137928,
      "name": "gotoxy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291670720,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1434",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291670720,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276115414,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1434",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276115414,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585528032,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1434",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528032,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585397856,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1434",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585397856,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717440,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1434",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717440,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void gotoxy(struct vc_data * vc, int new_x, int new_y)
```

```json
{
  "name": "gotoxy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585825472,
      "name": "gotoxy",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:1434",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:putconsxy",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal",
        "drivers/tty/vt/vt.c:restore_cur",
        "drivers/tty/vt/vt.c:set_mode",
        "drivers/tty/vt/vt.c:vc_do_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825472,
      "name": "gotoxy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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

# Function: <code>start_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957760,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1015",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957760,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291728,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1021",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291728,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584473792,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1021",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473792,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584563968,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:786",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563968,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584969856,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:798",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969856,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585203248,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:807",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585203248,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585321520,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:808",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321520,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585533584,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533584,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585674464,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585674464,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586401856,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:811",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_fast",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_closing",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401856,
      "name": "start_tty",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586516416,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:809",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_fast",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_closing",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586516416,
      "name": "start_tty",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586401328,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:825",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_fast",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401328,
      "name": "start_tty",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586939514,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:820",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_send_xchar"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_char",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586939024,
      "name": "start_tty",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588233318,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_send_xchar"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_char",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588232784,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589644070,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:804",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_send_xchar"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_closing",
        "drivers/tty/n_tty.c:n_tty_receive_char",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589643504,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589947926,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:805",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_send_xchar"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_closing",
        "drivers/tty/n_tty.c:n_tty_receive_char",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589947168,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590286342,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:803",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_send_xchar"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_closing",
        "drivers/tty/n_tty.c:n_tty_receive_char",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590285792,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498347792,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_signal_char",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498347792,
      "name": "start_tty",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231039988,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231039988,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291536624,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291536624,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276029636,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276029636,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585435488,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435488,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585305536,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305536,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585624864,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585624864,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void start_tty(struct tty_struct * tty)
```

```json
{
  "name": "start_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585733184,
      "name": "start_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:810",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/vt/keyboard.c:fn_hold"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585733184,
      "name": "start_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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

# Function: <code>tty_schedule_flip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583999481,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:398",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999520,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584331209,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:373",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331248,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584513113,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:373",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513152,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584592393,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:399",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592432,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585004569,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:400",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585004608,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585238677,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:400",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585238720,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585357989,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358032,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585571557,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571504,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585712597,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585712544,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586443157,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586441728,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586557637,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:mouse_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586556240,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586442597,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:mouse_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586441200,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586968821,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:413",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:mouse_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586967408,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498401376,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498401424,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231076048,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231076092,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291585036,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291584912,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276062178,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276062220,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585473621,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585473568,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585343637,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343584,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585662997,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585662944,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tty_schedule_flip(struct tty_port * port)
```

```json
{
  "name": "tty_schedule_flip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585771109,
      "name": "tty_schedule_flip",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:405",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_flip_buffer_push"
      ],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771056,
      "name": "tty_schedule_flip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void tty_schedule_flip(struct tty_port * port)
```
</details>
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

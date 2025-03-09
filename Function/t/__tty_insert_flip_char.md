# Function: <code>__tty_insert_flip_char</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584593632,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:373",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593632,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585005808,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:374",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585005808,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585239936,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:374",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239936,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585359296,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585359296,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585572880,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585572880,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585713920,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713920,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586443040,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586443040,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586557520,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586557520,
      "name": "__tty_insert_flip_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586442480,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586442480,
      "name": "__tty_insert_flip_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586968448,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:387",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586968448,
      "name": "__tty_insert_flip_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588264480,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:388",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264480,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589678143,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:393",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596233222,
      "name": "__tty_insert_flip_char.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589678096,
      "name": "__tty_insert_flip_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589983231,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:393",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596761235,
      "name": "__tty_insert_flip_char.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589983184,
      "name": "__tty_insert_flip_char",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
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
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498402552,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498402552,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231077444,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/rda-uart.c:rda_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231077444,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291587168,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvsi.c:hvsi_insert_chars",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291587168,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276063616,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276063616,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585474944,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474944,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585344960,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585344960,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585664320,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664320,
      "name": "__tty_insert_flip_char",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```

```json
{
  "name": "__tty_insert_flip_char",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585772432,
      "name": "__tty_insert_flip_char",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:379",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/tty/vt/keyboard.c:k_shift",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:fn_enter",
        "drivers/tty/vt/keyboard.c:handle_diacr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/vt.c:respond_string",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772432,
      "name": "__tty_insert_flip_char",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int __tty_insert_flip_char(struct tty_port * port, unsigned char ch, char flag)
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

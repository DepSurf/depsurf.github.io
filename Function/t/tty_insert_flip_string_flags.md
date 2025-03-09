# Function: <code>tty_insert_flip_string_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000016,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:366",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_event",
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
      "addr": 18446744071584000016,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331728,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:341",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071584331728,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584513616,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:341",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071584513616,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584593008,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:341",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593008,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585005184,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:342",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585005184,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585239504,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:342",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239504,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585358864,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358864,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585572016,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585572016,
      "name": "tty_insert_flip_string_flags",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585713056,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713056,
      "name": "tty_insert_flip_string_flags",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586442176,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586442176,
      "name": "tty_insert_flip_string_flags",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586556656,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586556656,
      "name": "tty_insert_flip_string_flags",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586441616,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586441616,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586967824,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:352",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586967824,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588263632,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:353",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263632,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589677312,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:358",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589677312,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589981920,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:358",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589981920,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498402088,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498402088,
      "name": "tty_insert_flip_string_flags",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231076592,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231076592,
      "name": "tty_insert_flip_string_flags",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291585824,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291585824,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276062800,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276062800,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474080,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474080,
      "name": "tty_insert_flip_string_flags",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585344096,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585344096,
      "name": "tty_insert_flip_string_flags",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585663456,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663456,
      "name": "tty_insert_flip_string_flags",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585771568,
      "name": "tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:347",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771568,
      "name": "tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int tty_insert_flip_string_flags(struct tty_port * port, const unsigned char * chars, const char * flags, size_t size)
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

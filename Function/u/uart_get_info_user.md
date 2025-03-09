# Function: <code>uart_get_info_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584101026,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:718",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584434584,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:773",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584617832,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:765",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584699041,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:766",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585111851,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:774",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585348048,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:781",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585454448,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:801",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454448,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585670352,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:795",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670352,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585811296,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:796",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585811296,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586541968,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:797",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586541968,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586652944,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:798",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652944,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586536864,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:796",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586536864,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587075280,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:779",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075280,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379280,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:791",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379280,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589803424,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:797",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589803424,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590108384,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:818",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590108384,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590447936,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:812",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590447936,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498532232,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:796",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498532232,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231181324,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:796",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231181324,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291747056,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:796",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291747056,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276150996,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:796",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276150996,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585572288,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:796",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585572288,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437488,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:796",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437488,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585761696,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:796",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585761696,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```

```json
{
  "name": "uart_get_info_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869920,
      "name": "uart_get_info_user",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:796",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869920,
      "name": "uart_get_info_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int uart_get_info_user(struct tty_struct * tty, struct serial_struct * ss)
```
</details>
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

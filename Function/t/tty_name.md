# Function: <code>tty_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583954224,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:250",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954224,
      "name": "tty_name",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584303483,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:243",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286192,
      "name": "tty_name",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584485547,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:243",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468288,
      "name": "tty_name",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584560391,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:244",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552848,
      "name": "tty_name",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584976778,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:245",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584963760,
      "name": "tty_name",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585208264,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:245",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585197504,
      "name": "tty_name",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585326392,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585315232,
      "name": "tty_name",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585538316,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528016,
      "name": "tty_name",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585679228,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668880,
      "name": "tty_name",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586416279,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:247",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586395040,
      "name": "tty_name",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591458143,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:244",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586510080,
      "name": "tty_name",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591399967,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:245",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586395312,
      "name": "tty_name",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592446396,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:245",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586922048,
      "name": "tty_name",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594314526,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:244",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588215344,
      "name": "tty_name",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589644344,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:243",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589624432,
      "name": "tty_name",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589948200,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:244",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589927952,
      "name": "tty_name",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590286616,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:244",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:tty_release_checks",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590266272,
      "name": "tty_name",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498355260,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498340288,
      "name": "tty_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231041456,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231031704,
      "name": "tty_name",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291532672,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291521232,
      "name": "tty_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276033892,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276023462,
      "name": "tty_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585440252,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585429904,
      "name": "tty_name",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585310284,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585299952,
      "name": "tty_name",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585629628,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619280,
      "name": "tty_name",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585740660,
      "name": "tty_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:246",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:check_tty_count"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/serial/serial_core.c:uart_set_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585727408,
      "name": "tty_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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

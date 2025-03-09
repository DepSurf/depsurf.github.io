# Function: <code>tty_driver_name</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584303491,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:252",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296848,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584485555,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:252",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478912,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584560401,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:253",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566272,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584976788,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:254",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584977872,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585208276,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:254",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211232,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585326404,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585330176,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585538329,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585542832,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585679241,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683744,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586416468,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:256",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586411168,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591458332,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:253",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586526816,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591400156,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:254",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586411776,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592446585,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:253",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938592,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594314434,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:252",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588232256,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589644364,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:251",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642912,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589948220,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:252",
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
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589946576,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590286636,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:252",
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
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_port.c:tty_port_close_start",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590285200,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498355244,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498361128,
      "name": "tty_driver_name",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231041240,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231046904,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291532652,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291545040,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276033884,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276036646,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585440265,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585444768,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585310297,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314800,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585629641,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585634144,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * tty_driver_name(const struct tty_struct * tty)
```

```json
{
  "name": "tty_driver_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585740673,
      "name": "tty_driver_name",
      "external": true,
      "loc": "drivers/tty/tty_io.c:255",
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
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/n_tty.c:n_tty_receive_char_flagged",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742272,
      "name": "tty_driver_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
const char * tty_driver_name(const struct tty_struct * tty)
```
</details>
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

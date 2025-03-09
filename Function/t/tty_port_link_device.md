# Function: <code>tty_port_link_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002112,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:46",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/tty_port.c:tty_port_register_device_attr",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002112,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333520,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:46",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333520,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515376,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:46",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515376,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584595099,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:86",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ],
      "caller_func": [
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595040,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585007088,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:87",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585007088,
      "name": "tty_port_link_device",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585240624,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:87",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585240624,
      "name": "tty_port_link_device",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585360032,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:87",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585360032,
      "name": "tty_port_link_device",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:87",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585577277,
      "name": "tty_port_link_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585574256,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585715413,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585715264,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586446245,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586444480,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586560734,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586558960,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586445822,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:89",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586443920,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586972062,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:89",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970144,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588268142,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:98",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266048,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589682926,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:119",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680576,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589987534,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:119",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589985184,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590326058,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:117",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590323696,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498404872,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498404872,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231078804,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231078804,
      "name": "tty_port_link_device",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291589584,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/hvc/hvsi.c:hvsi_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291589584,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276065088,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276065088,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585476437,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476288,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585346453,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346304,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585665813,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585665664,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void tty_port_link_device(struct tty_port * port, struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_port_link_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585773925,
      "name": "tty_port_link_device",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773776,
      "name": "tty_port_link_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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

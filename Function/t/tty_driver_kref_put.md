# Function: <code>tty_driver_kref_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583959605,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3458",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959632,
      "name": "tty_driver_kref_put",
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584293189,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3454",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293216,
      "name": "tty_driver_kref_put",
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584475253,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3454",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475280,
      "name": "tty_driver_kref_put",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584558960,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3007",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558960,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584971657,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3114",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971680,
      "name": "tty_driver_kref_put",
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585204485,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3135",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204528,
      "name": "tty_driver_kref_put",
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585323045,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3290",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323088,
      "name": "tty_driver_kref_put",
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585535109,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3294",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585535056,
      "name": "tty_driver_kref_put",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585675989,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3290",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675936,
      "name": "tty_driver_kref_put",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586403013,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3293",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586402944,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586529856,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3386",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586518128,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586402789,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3435",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586402720,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586942230,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3435",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_remove",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586929568,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588236877,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3408",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588222048,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589647468,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3405",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589631152,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589951330,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3411",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589934816,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590289824,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3428",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590273360,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498346304,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3290",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498346304,
      "name": "tty_driver_kref_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231037804,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3290",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231037804,
      "name": "tty_driver_kref_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291533952,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3290",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291533952,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276029106,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3290",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276029152,
      "name": "tty_driver_kref_put",
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
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585437013,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3290",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436960,
      "name": "tty_driver_kref_put",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585307061,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3290",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585307008,
      "name": "tty_driver_kref_put",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585626389,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3290",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585626336,
      "name": "tty_driver_kref_put",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void tty_driver_kref_put(struct tty_driver * driver)
```

```json
{
  "name": "tty_driver_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585738341,
      "name": "tty_driver_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3290",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738288,
      "name": "tty_driver_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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

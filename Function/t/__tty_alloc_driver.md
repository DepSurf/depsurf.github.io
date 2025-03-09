# Function: <code>__tty_alloc_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583959264,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3368",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959264,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584296272,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3364",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296272,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584478336,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3364",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478336,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584565680,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2922",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584565680,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584977280,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3029",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584977280,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585210656,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3050",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210656,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585329600,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3205",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585329600,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585542240,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3209",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585542240,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585683152,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3205",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683152,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586410544,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3208",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_init",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586410544,
      "name": "__tty_alloc_driver.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071586410896,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586526192,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3301",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_init",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586526192,
      "name": "__tty_alloc_driver.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071586526544,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586405504,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3350",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586405504,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586932288,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3350",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586932288,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588231296,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3317",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231296,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589641696,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3315",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589641696,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589945344,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3321",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589945344,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590284448,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3338",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/pty.c:legacy_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590284448,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498352416,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3205",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498352416,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231046324,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3205",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231046324,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291544096,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3205",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvsi.c:hvsi_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291544096,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276034224,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3205",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276034224,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585444176,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3205",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585444176,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585314208,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3205",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314208,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585633552,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3205",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585633552,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct tty_driver * __tty_alloc_driver(unsigned int lines, struct module * owner, long unsigned int flags)
```

```json
{
  "name": "__tty_alloc_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585741680,
      "name": "__tty_alloc_driver",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3205",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585741680,
      "name": "__tty_alloc_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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

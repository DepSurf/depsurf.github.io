# Function: <code>register_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579730064,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2491",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579730064,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752368,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2610",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752368,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579778528,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2437",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778528,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774256,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2410",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774256,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 893
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579806720,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2398",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806720,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2567",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848550,
      "name": "register_console.cold.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071579840272,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2573",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895590,
      "name": "register_console.cold.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579887008,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2638",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579930376,
      "name": "register_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579921552,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 845
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2648",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980522,
      "name": "register_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579971616,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580021280,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2725",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020640,
      "name": "register_console.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
    },
    {
      "addr": 18446744071580028070,
      "name": "register_console.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071580021280,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999152,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2807",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/debug/debug_core.c:opt_kgdb_con",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998528,
      "name": "register_console.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071591301812,
      "name": "register_console.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579999152,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002016,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2870",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/debug/debug_core.c:opt_kgdb_con",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001472,
      "name": "register_console.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    },
    {
      "addr": 18446744071591244597,
      "name": "register_console.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071580002016,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580134832,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2930",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/debug/debug_core.c:opt_kgdb_con",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134224,
      "name": "register_console.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
    },
    {
      "addr": 18446744071592133429,
      "name": "register_console.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071580134832,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580276832,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:3104",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/debug/debug_core.c:opt_kgdb_con",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276256,
      "name": "register_console.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071593904236,
      "name": "register_console.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071580276832,
      "name": "register_console",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:3312",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/debug/debug_core.c:opt_kgdb_con",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/earlycon.c:register_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595985530,
      "name": "register_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580484832,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:3353",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/debug/debug_core.c:opt_kgdb_con",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/earlycon.c:register_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596503840,
      "name": "register_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580556800,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:3422",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "kernel/debug/debug_core.c:opt_kgdb_con",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/earlycon.c:register_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597401799,
      "name": "register_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580625744,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1343
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491156728,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2648",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/tty/serial/meson_uart.c:meson_serial_console_init",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_init",
        "drivers/tty/serial/owl-uart.c:owl_uart_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491156728,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225183996,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2648",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "fs/pstore/platform.c:pstore_register",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/tty/serial/meson_uart.c:meson_serial_console_init",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_init",
        "drivers/tty/serial/owl-uart.c:owl_uart_console_init",
        "drivers/tty/serial/rda-uart.c:rda_uart_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225183996,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284052944,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2648",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/udbg.c:register_early_udbg_console",
        "kernel/debug/debug_core.c:kgdb_register_io_module",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvsi.c:hvsi_console_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284052944,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1684
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
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271710346,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2648",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/tty/serial/sifive.c:sifive_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271710346,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 786
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2648",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949258,
      "name": "register_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579940352,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2648",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887146,
      "name": "register_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579878496,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 839
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2648",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940794,
      "name": "register_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579931888,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void register_console(struct console * newcon)
```

```json
{
  "name": "register_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2648",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_console_register",
        "drivers/tty/vt/vt.c:con_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/hvc/hvc_console.c:hvc_console_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:univ8250_console_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_register_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987114,
      "name": "register_console.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579977824,
      "name": "register_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 914
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

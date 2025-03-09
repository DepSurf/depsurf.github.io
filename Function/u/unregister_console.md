# Function: <code>unregister_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579729808,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2653",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729808,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752112,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2772",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752112,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579778272,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2598",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778272,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774000,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2572",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774000,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579806464,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2560",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806464,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848352,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2729",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848352,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579895392,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2739",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895392,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579930178,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2804",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579930178,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980322,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2814",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980322,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027858,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2862",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027858,
      "name": "unregister_console",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591301600,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2943",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591301600,
      "name": "unregister_console",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591244385,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:3007",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591244385,
      "name": "unregister_console",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592133217,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:3066",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592133217,
      "name": "unregister_console",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593904023,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:3226",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593904023,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474048,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:3483",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474048,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545648,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:3524",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/serial/serial_core.c:serial_core_remove_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545648,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607568,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:3611",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/serial/serial_core.c:serial_core_remove_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607568,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491165440,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2814",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491165440,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225191880,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2814",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225191880,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284064056,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2814",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284064056,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271718908,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2814",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271718908,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949058,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2814",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949058,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886946,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2814",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886946,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940594,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2814",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940594,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int unregister_console(struct console * console)
```

```json
{
  "name": "unregister_console",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986866,
      "name": "unregister_console",
      "external": true,
      "loc": "kernel/printk/printk.c:2814",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:register_console",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986866,
      "name": "unregister_console",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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

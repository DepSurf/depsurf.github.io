# Function: <code>tty_port_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584002640,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:131",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002640,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584334112,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:131",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334032,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584515968,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:131",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515888,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584595658,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:244",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_put"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595568,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585007872,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:245",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585007792,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585242016,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:245",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241936,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585361424,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:245",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585361344,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585575076,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:245",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_disallocate_all",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585574992,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585716032,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585715952,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586444848,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586444752,
      "name": "tty_port_destroy",
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586559328,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586559232,
      "name": "tty_port_destroy",
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586444288,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:247",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586444192,
      "name": "tty_port_destroy",
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586970704,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:247",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970608,
      "name": "tty_port_destroy",
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588266795,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:258",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266704,
      "name": "tty_port_destroy",
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589681435,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:279",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589681328,
      "name": "tty_port_destroy",
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589986043,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:279",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589985936,
      "name": "tty_port_destroy",
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590324555,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:279",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590324448,
      "name": "tty_port_destroy",
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498405680,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498405680,
      "name": "tty_port_destroy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231079412,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231079412,
      "name": "tty_port_destroy",
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291591096,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_put"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvsi.c:hvsi_console_init",
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291590864,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276066030,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_put"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276065906,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585477056,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476976,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585346992,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346912,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585666432,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666352,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tty_port_destroy(struct tty_port * port)
```

```json
{
  "name": "tty_port_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585774544,
      "name": "tty_port_destroy",
      "external": true,
      "loc": "drivers/tty/tty_port.c:246",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_destructor"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_unregister_driver",
        "drivers/tty/serial/serial_core.c:uart_register_driver",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install",
        "drivers/char/ttyprintk.c:ttyprintk_exit",
        "drivers/char/ttyprintk.c:ttyprintk_init",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585774464,
      "name": "tty_port_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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

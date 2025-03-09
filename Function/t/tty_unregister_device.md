# Function: <code>tty_unregister_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583957056,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3348",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957056,
      "name": "tty_unregister_device",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584290928,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3344",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290928,
      "name": "tty_unregister_device",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584473008,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3344",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473008,
      "name": "tty_unregister_device",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584558880,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2902",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_driver_kref_put",
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558880,
      "name": "tty_unregister_device",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584969392,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3009",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969392,
      "name": "tty_unregister_device",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585202768,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3030",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202768,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585321040,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3185",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321040,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585533104,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3189",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533104,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585673984,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3185",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673984,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586398688,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3188",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398688,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586513712,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3281",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513712,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586398640,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3330",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398640,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586925328,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3330",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925328,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588219168,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3297",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219168,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589628624,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3295",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589628624,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589932320,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3302",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589932320,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590270832,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3319",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590270832,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498346200,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3185",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_driver_kref_put",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498346200,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231037708,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3185",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_driver_kref_put",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231037708,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291533760,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3185",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_driver_kref_put",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291533760,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276028746,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3185",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276028746,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585435008,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3185",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435008,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585305056,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3185",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305056,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585624384,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3185",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585624384,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void tty_unregister_device(struct tty_driver * driver, unsigned int index)
```

```json
{
  "name": "tty_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585732704,
      "name": "tty_unregister_device",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3185",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:destruct_tty_driver",
        "drivers/tty/tty_port.c:tty_port_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585732704,
      "name": "tty_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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

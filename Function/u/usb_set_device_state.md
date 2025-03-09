# Function: <code>usb_set_device_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585154320,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2007",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585154320,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585546752,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2004",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546752,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585734096,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:1923",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585734096,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585821280,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:1945",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821280,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586260544,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:1945",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586260544,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586517712,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:1969",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586517712,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666288,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:1980",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666288,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586920496,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2018",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920496,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587118944,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2029",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587118944,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587972646,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2036",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:register_root_hub",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965248,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588032397,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2036",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:register_root_hub",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025008,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587913821,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2043",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:register_root_hub",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587906960,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588523709,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2046",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:register_root_hub",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588516416,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589931709,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2046",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:register_root_hub",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589924048,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591513206,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2056",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:register_root_hub",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591505088,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591934582,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2070",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:register_root_hub",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591926928,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592675014,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2108",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:register_root_hub",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592666768,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500198288,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2029",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500198288,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232672936,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2029",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232672936,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293477920,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2029",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293477920,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277117284,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2029",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277117284,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586825024,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2029",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586825024,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586766800,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2029",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766800,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587073504,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2029",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587073504,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void usb_set_device_state(struct usb_device * udev, enum usb_device_state new_state)
```

```json
{
  "name": "usb_set_device_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587180880,
      "name": "usb_set_device_state",
      "external": true,
      "loc": "drivers/usb/core/hub.c:2029",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587180880,
      "name": "usb_set_device_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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

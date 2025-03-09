# Function: <code>usb_put_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585149136,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:547",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:usbdev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585149136,
      "name": "usb_put_dev",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541520,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:552",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541520,
      "name": "usb_put_dev",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585729408,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:566",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585729408,
      "name": "usb_put_dev",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585816720,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:702",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585816720,
      "name": "usb_put_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586255968,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:702",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255968,
      "name": "usb_put_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586513296,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:703",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513296,
      "name": "usb_put_dev",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661968,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:703",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661968,
      "name": "usb_put_dev",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586916192,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586916192,
      "name": "usb_put_dev",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587114640,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587114640,
      "name": "usb_put_dev",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587961312,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_put_invalidate_rhdev",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961312,
      "name": "usb_put_dev",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588021136,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:709",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_put_invalidate_rhdev",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588021136,
      "name": "usb_put_dev",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587902832,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:755",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_put_invalidate_rhdev",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587902832,
      "name": "usb_put_dev",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588512048,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:755",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_put_invalidate_rhdev",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588512048,
      "name": "usb_put_dev",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589919312,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:713",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_put_invalidate_rhdev",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589919312,
      "name": "usb_put_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591499728,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:713",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591499728,
      "name": "usb_put_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591921040,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:789",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591921040,
      "name": "usb_put_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592660880,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:777",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592660880,
      "name": "usb_put_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500187840,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500187840,
      "name": "usb_put_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232667944,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232667944,
      "name": "usb_put_dev",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293469248,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293469248,
      "name": "usb_put_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277114424,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277114424,
      "name": "usb_put_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586820720,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586820720,
      "name": "usb_put_dev",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586762496,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586762496,
      "name": "usb_put_dev",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587069200,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069200,
      "name": "usb_put_dev",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device * dev)
```

```json
{
  "name": "usb_put_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587176368,
      "name": "usb_put_dev",
      "external": true,
      "loc": "drivers/usb/core/usb.c:722",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_release_interface",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176368,
      "name": "usb_put_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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

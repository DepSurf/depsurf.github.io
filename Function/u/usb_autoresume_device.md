# Function: <code>usb_autoresume_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585221680,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1564",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221680,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585614816,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1574",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585614816,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585802352,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1577",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585802352,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585888768,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1595",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585888768,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586329280,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1603",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586329280,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586586480,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1603",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586480,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586735488,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1600",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735488,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586990704,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1595",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586990704,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587189776,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1597",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587189776,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588039412,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1695",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:proc_wait_for_resume",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588043856,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588088292,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1705",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:proc_wait_for_resume",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092704,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587970836,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1701",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975488,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588582468,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1701",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588587200,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589995156,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1703",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589999504,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591591012,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1703",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591595776,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592012820,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1703",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592017616,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592752996,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1709",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592757888,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500273904,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1597",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500273904,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232744528,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1597",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232744528,
      "name": "usb_autoresume_device",
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293573200,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1597",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293573200,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277185070,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1597",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277185070,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586895856,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1597",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895856,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586836976,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1597",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586836976,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587144336,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1597",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587144336,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int usb_autoresume_device(struct usb_device * udev)
```

```json
{
  "name": "usb_autoresume_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587251408,
      "name": "usb_autoresume_device",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1597",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_remote_wakeup",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587251408,
      "name": "usb_autoresume_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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

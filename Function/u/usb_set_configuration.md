# Function: <code>usb_set_configuration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585213984,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1729",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585213984,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2273
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607088,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1726",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607088,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2349
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585794656,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1729",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794656,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2314
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585881120,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1727",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585881120,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2116
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586321584,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1766",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586321584,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2122
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586579120,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1803",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586579120,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2176
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586728048,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1803",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586728048,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2219
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1805",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586985642,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071586982624,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1990
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1805",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587184682,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071587181664,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1990
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1806",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:proc_setconfig",
        "drivers/usb/core/generic.c:usb_generic_driver_disconnect",
        "drivers/usb/core/generic.c:usb_generic_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588035500,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071588032336,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1951",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:proc_setconfig",
        "drivers/usb/core/generic.c:usb_generic_driver_disconnect",
        "drivers/usb/core/generic.c:usb_generic_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591547242,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071588082272,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2079
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1957",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:usb_generic_driver_disconnect",
        "drivers/usb/core/generic.c:usb_generic_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591489584,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071587965072,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2075
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1957",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:usb_generic_driver_disconnect",
        "drivers/usb/core/generic.c:usb_generic_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592567248,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071588576160,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1957",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:usb_generic_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594446223,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071589987600,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2446
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591582272,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1958",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:usb_generic_driver_probe",
        "drivers/usb/core/generic.c:usb_generic_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591582272,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2662
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592004064,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1992",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:usb_generic_driver_probe",
        "drivers/usb/core/generic.c:usb_generic_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592004064,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2693
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592744128,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1993",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:usb_generic_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592744128,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2783
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500264968,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1805",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500264968,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2288
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232736532,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1805",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232736532,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2208
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293562064,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1805",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293562064,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2636
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277177792,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1805",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277177792,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1866
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1805",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586890762,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071586887744,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1990
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1805",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586831882,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071586828864,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1990
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1805",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587139242,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071587136224,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1990
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
int usb_set_configuration(struct usb_device * dev, int configuration)
```

```json
{
  "name": "usb_set_configuration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_set_configuration",
      "external": true,
      "loc": "drivers/usb/core/message.c:1805",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_authorize_device",
        "drivers/usb/core/hub.c:usb_deauthorize_device",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/sysfs.c:remove_store",
        "drivers/usb/core/sysfs.c:bConfigurationValue_store",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/generic.c:generic_disconnect",
        "drivers/usb/core/generic.c:generic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246330,
      "name": "usb_set_configuration.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071587243312,
      "name": "usb_set_configuration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1988
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

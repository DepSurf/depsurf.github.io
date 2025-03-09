# Function: <code>usb_get_descriptor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585208608,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:633",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585208608,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585600800,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:630",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585600800,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585788368,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:633",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585788368,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585874928,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:631",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874928,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586315296,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:635",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586315296,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586571648,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:636",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586571648,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721024,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721024,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586976032,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586976032,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587175072,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587175072,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588025376,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:645",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025376,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588075216,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:780",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588075216,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587958000,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:780",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587958000,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588568912,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:780",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588568912,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589979856,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:780",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589979856,
      "name": "usb_get_descriptor",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591573440,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:780",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591573440,
      "name": "usb_get_descriptor",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591995200,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:780",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591995200,
      "name": "usb_get_descriptor",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592735072,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:781",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592735072,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500256120,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500256120,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232730004,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232730004,
      "name": "usb_get_descriptor",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293552096,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293552096,
      "name": "usb_get_descriptor",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277170862,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277170862,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586881152,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881152,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586822272,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586822272,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587129632,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129632,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int usb_get_descriptor(struct usb_device * dev, unsigned char type, unsigned char index, void * buf, int size)
```

```json
{
  "name": "usb_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587237088,
      "name": "usb_get_descriptor",
      "external": true,
      "loc": "drivers/usb/core/message.c:637",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:descriptors_changed",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/message.c:usb_get_device_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587237088,
      "name": "usb_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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

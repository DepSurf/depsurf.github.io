# Function: <code>usb_enable_lpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585156992,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4092",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585156992,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585549504,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4093",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585549504,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585736672,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4019",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585736672,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585825040,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4038",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825040,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586263792,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4041",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263792,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586521440,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4092",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586521440,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586670048,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4154",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670048,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586923584,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4201",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923584,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587122032,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4249",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587122032,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587971472,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4263",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587971472,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588031232,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4281",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588031232,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587912432,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4401",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912432,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588522320,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4405",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588522320,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589930448,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4411",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_disable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589930448,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591511888,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4402",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_disable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591511888,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591933264,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4422",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_disable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591933264,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592673696,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4431",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_disable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592673696,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500196456,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4249",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500196456,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232677060,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4249",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232677060,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293477584,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4249",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293477584,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277120054,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4249",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277120054,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586828112,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4249",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828112,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586769888,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4249",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769888,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587076592,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4249",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587076592,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void usb_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587183968,
      "name": "usb_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4249",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_unlocked_enable_lpm",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/port.c:usb3_lpm_permit_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587183968,
      "name": "usb_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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

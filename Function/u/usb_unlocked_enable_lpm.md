# Function: <code>usb_unlocked_enable_lpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585157152,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4120",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585157152,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585549760,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4132",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585549760,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585736928,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4058",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585736928,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585825296,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4077",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825296,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586264048,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4080",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586264048,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586521696,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4131",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586521696,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586670304,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4193",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670304,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586923840,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4240",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923840,
      "name": "usb_unlocked_enable_lpm",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587122288,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4288",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587122288,
      "name": "usb_unlocked_enable_lpm",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587981426,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4302",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972032,
      "name": "usb_unlocked_enable_lpm",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588041095,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4320",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588031792,
      "name": "usb_unlocked_enable_lpm",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587923047,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4440",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912992,
      "name": "usb_unlocked_enable_lpm",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588533015,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4444",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588522880,
      "name": "usb_unlocked_enable_lpm",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589941269,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4450",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589931056,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591523849,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4441",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591512512,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591945778,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4461",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591933888,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592685570,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4470",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592674320,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500196704,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4288",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500196704,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232677324,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4288",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232677324,
      "name": "usb_unlocked_enable_lpm",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293479520,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4288",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293479520,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277121002,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4288",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277121002,
      "name": "usb_unlocked_enable_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586828368,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4288",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828368,
      "name": "usb_unlocked_enable_lpm",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586770144,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4288",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586770144,
      "name": "usb_unlocked_enable_lpm",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587076848,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4288",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587076848,
      "name": "usb_unlocked_enable_lpm",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void usb_unlocked_enable_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_unlocked_enable_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587184224,
      "name": "usb_unlocked_enable_lpm",
      "external": true,
      "loc": "drivers/usb/core/hub.c:4288",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587184224,
      "name": "usb_unlocked_enable_lpm",
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

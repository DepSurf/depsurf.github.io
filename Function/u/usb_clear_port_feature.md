# Function: <code>usb_clear_port_feature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585158912,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:396",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:usb_hub_set_port_power",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158912,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585551536,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:398",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:usb_hub_set_port_power",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551536,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738704,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:401",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:usb_hub_set_port_power",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738704,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585826432,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:410",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:usb_hub_set_port_power",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826432,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586265728,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:410",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586265728,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586523120,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:413",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586523120,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586671728,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:414",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671728,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586925856,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:416",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925856,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587124304,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:418",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587124304,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587992181,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:420",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_handle_remote_wakeup",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587982752,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588051797,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:420",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_handle_remote_wakeup",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588042416,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587934408,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:427",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587924368,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588544584,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:427",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588534432,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589954070,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:427",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942704,
      "name": "usb_clear_port_feature",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591538727,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:431",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:disable_store",
        "drivers/usb/core/port.c:disable_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591525520,
      "name": "usb_clear_port_feature",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591960406,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:431",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:disable_store",
        "drivers/usb/core/port.c:disable_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591947408,
      "name": "usb_clear_port_feature",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592700054,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:451",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:disable_store",
        "drivers/usb/core/port.c:disable_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592687200,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500199968,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:418",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500199968,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232678648,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:418",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232678648,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293484960,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:418",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293484960,
      "name": "usb_clear_port_feature",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277123888,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:418",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277123888,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586830384,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:418",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586830384,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586772144,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:418",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586772144,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587078864,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:418",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078864,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int usb_clear_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "usb_clear_port_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587186016,
      "name": "usb_clear_port_feature",
      "external": true,
      "loc": "drivers/usb/core/hub.c:418",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587186016,
      "name": "usb_clear_port_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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

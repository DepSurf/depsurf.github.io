# Function: <code>usb_hcd_alloc_bandwidth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199376,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1958",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199376,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585591520,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1954",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585591520,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585779136,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1955",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779136,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585866128,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1969",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585866128,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 789
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586306000,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1958",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586306000,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586563104,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1960",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586563104,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 879
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586712032,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1944",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586712032,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 879
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586964464,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1833",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964464,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587163472,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1830",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587163472,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588012928,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1827",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588012928,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588065152,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1837",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588065152,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587947936,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1837",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587947936,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588558448,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1858",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588558448,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1013
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589968592,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1861",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589968592,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591561552,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1862",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591561552,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591983312,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1866",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591983312,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592723232,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1841",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592723232,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500243192,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1830",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500243192,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232719408,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1830",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232719408,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293537232,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1830",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293537232,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277161256,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1830",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277161256,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586869552,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1830",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586869552,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586810752,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1830",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586810752,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587118032,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1830",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587118032,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int usb_hcd_alloc_bandwidth(struct usb_device * udev, struct usb_host_config * new_config, struct usb_host_interface * cur_alt, struct usb_host_interface * new_alt)
```

```json
{
  "name": "usb_hcd_alloc_bandwidth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587225216,
      "name": "usb_hcd_alloc_bandwidth",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1830",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587225216,
      "name": "usb_hcd_alloc_bandwidth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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

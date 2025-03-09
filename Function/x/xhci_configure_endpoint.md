# Function: <code>xhci_configure_endpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585461264,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2637",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_update_hub_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585461264,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585856896,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2615",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856896,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1266
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586045728,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2604",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045728,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1266
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586127552,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2548",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586127552,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1402
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586570560,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2559",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586570560,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1503
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586835328,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2685",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586835328,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1517
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586991488,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2702",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586991488,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1615
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2731",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587251264,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1205
    },
    {
      "addr": 18446744071587266299,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2740",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587451664,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1205
    },
    {
      "addr": 18446744071587466722,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2743",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588314688,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
    },
    {
      "addr": 18446744071588329007,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2876",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588349408,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1217
    },
    {
      "addr": 18446744071591563356,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2871",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588232144,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1217
    },
    {
      "addr": 18446744071591506105,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2883",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877024,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1254
    },
    {
      "addr": 18446744071592607374,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2921",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590304880,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1283
    },
    {
      "addr": 18446744071594490373,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591929344,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2919",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591929344,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1846
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592351872,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2759",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592351872,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1839
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593093584,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2789",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593093584,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1839
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500587592,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2740",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500587592,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1764
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233048832,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2740",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233048832,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1824
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293994400,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2740",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293994400,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2356
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277459496,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2740",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277459496,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1486
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2740",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587157696,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1205
    },
    {
      "addr": 18446744071587172754,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2740",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586916304,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1205
    },
    {
      "addr": 18446744071586931496,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2740",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587406224,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1205
    },
    {
      "addr": 18446744071587421282,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
int xhci_configure_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct xhci_command * command, bool ctx_change, bool must_succeed)
```

```json
{
  "name": "xhci_configure_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_configure_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:2740",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587512624,
      "name": "xhci_configure_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1255
    },
    {
      "addr": 18446744071587528011,
      "name": "xhci_configure_endpoint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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

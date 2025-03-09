# Function: <code>usb_hcd_giveback_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585189632,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1824",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189632,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585581696,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1820",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585581696,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585769344,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1821",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585769344,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585855984,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1835",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585855984,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586295904,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1824",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295904,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586553392,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1826",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553392,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702256,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1810",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702256,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586957616,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1712",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957616,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587156304,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1709",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587156304,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588006256,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1706",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588006256,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588058752,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1716",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588058752,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587942320,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1716",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587942320,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1737",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592565065,
      "name": "usb_hcd_giveback_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588552768,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1743",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594443832,
      "name": "usb_hcd_giveback_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589961472,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1744",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596271722,
      "name": "usb_hcd_giveback_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591552096,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1748",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596801538,
      "name": "usb_hcd_giveback_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071591973712,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1723",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597725144,
      "name": "usb_hcd_giveback_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071592713552,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500235128,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1709",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500235128,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232710732,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1709",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_urb_in_irq",
        "drivers/usb/musb/musb_host.c:musb_giveback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232710732,
      "name": "usb_hcd_giveback_urb",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293525952,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1709",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293525952,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277154038,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1709",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277154038,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586862384,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1709",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586862384,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586803696,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1709",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586803696,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587110864,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1709",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587110864,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void usb_hcd_giveback_urb(struct usb_hcd * hcd, struct urb * urb, int status)
```

```json
{
  "name": "usb_hcd_giveback_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587218352,
      "name": "usb_hcd_giveback_urb",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1709",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587218352,
      "name": "usb_hcd_giveback_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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

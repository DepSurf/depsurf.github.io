# Function: <code>usb_hcd_unlink_urb_from_ep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585185936,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1345",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585185936,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585578048,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1337",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578048,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585765696,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1338",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585765696,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585852528,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1341",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585852528,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586292320,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1330",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586292320,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586553152,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1332",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553152,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701104,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1330",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701104,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586956448,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1235",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586956448,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587155136,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1235",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587155136,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588008845,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1236",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588005696,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588061053,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1237",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057424,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587946462,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1237",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587942064,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588556974,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1244",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552512,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589965861,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1244",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589957360,
      "name": "usb_hcd_unlink_urb_from_ep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591558757,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1244",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591546432,
      "name": "usb_hcd_unlink_urb_from_ep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591980508,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1248",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591968080,
      "name": "usb_hcd_unlink_urb_from_ep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592720444,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1223",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592707920,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500241140,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1235",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500233120,
      "name": "usb_hcd_unlink_urb_from_ep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232707068,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1235",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_urb_in_irq",
        "drivers/usb/musb/musb_host.c:musb_urb_enqueue",
        "drivers/usb/musb/musb_host.c:musb_urb_enqueue",
        "drivers/usb/musb/musb_host.c:musb_giveback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232707068,
      "name": "usb_hcd_unlink_urb_from_ep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293524336,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1235",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293524336,
      "name": "usb_hcd_unlink_urb_from_ep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277153406,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1235",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277153406,
      "name": "usb_hcd_unlink_urb_from_ep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586861216,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1235",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586861216,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586802608,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1235",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802608,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587109696,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1235",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587109696,
      "name": "usb_hcd_unlink_urb_from_ep",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void usb_hcd_unlink_urb_from_ep(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "usb_hcd_unlink_urb_from_ep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587214304,
      "name": "usb_hcd_unlink_urb_from_ep",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1235",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:dwc2_host_complete",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_done",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587214304,
      "name": "usb_hcd_unlink_urb_from_ep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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

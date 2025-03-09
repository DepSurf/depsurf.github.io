# Function: <code>usb_hcd_resume_root_hub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585187584,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2362",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187584,
      "name": "usb_hcd_resume_root_hub",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585579696,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2358",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585579696,
      "name": "usb_hcd_resume_root_hub",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585767344,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2359",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767344,
      "name": "usb_hcd_resume_root_hub",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585854096,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2373",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585854096,
      "name": "usb_hcd_resume_root_hub",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293888,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2362",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293888,
      "name": "usb_hcd_resume_root_hub",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586551216,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2377",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586551216,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586700064,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2361",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586700064,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586954848,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2250",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954848,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587153504,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2250",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587153504,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588003936,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2247",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588003936,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588057296,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2257",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057296,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587939680,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2257",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587939680,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588550064,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2408",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588550064,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589959616,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2411",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589959616,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591548288,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2405",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591548288,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591969904,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2409",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591969904,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592709744,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2384",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592709744,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500235528,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2250",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500235528,
      "name": "usb_hcd_resume_root_hub",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232708408,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2250",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/musb/musb_host.c:musb_host_poke_root_hub",
        "drivers/usb/musb/musb_host.c:musb_host_resume_root_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232708408,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293521952,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2250",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293521952,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277150978,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2250",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277150978,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586859584,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2250",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859584,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586801024,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2250",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586801024,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587108064,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2250",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587108064,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void usb_hcd_resume_root_hub(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_resume_root_hub",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587215568,
      "name": "usb_hcd_resume_root_hub",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2250",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:compliance_mode_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215568,
      "name": "usb_hcd_resume_root_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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

# Function: <code>xhci_handle_halted_endpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_handle_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_handle_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:861",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588269808,
      "name": "xhci_handle_halted_endpoint.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071591509395,
      "name": "xhci_handle_halted_endpoint.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_handle_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_handle_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:906",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588921328,
      "name": "xhci_handle_halted_endpoint.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    },
    {
      "addr": 18446744071592610969,
      "name": "xhci_handle_halted_endpoint.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_handle_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_handle_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590348496,
      "name": "xhci_handle_halted_endpoint.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071594493608,
      "name": "xhci_handle_halted_endpoint.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int xhci_handle_halted_endpoint(struct xhci_hcd * xhci, struct xhci_virt_ep * ep, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_handle_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591978560,
      "name": "xhci_handle_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:898",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591978560,
      "name": "xhci_handle_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
int xhci_handle_halted_endpoint(struct xhci_hcd * xhci, struct xhci_virt_ep * ep, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_handle_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592399984,
      "name": "xhci_handle_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:929",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592399984,
      "name": "xhci_handle_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
int xhci_handle_halted_endpoint(struct xhci_hcd * xhci, struct xhci_virt_ep * ep, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_handle_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593144880,
      "name": "xhci_handle_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:937",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593144880,
      "name": "xhci_handle_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int xhci_handle_halted_endpoint(struct xhci_hcd * xhci, struct xhci_virt_ep * ep, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

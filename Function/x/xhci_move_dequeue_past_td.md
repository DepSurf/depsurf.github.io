# Function: <code>xhci_move_dequeue_past_td</code>

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
  "name": "xhci_move_dequeue_past_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_move_dequeue_past_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:553",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588274704,
      "name": "xhci_move_dequeue_past_td.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071591509939,
      "name": "xhci_move_dequeue_past_td.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int xhci_move_dequeue_past_td(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td)
```

```json
{
  "name": "xhci_move_dequeue_past_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_move_dequeue_past_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:566",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588929600,
      "name": "xhci_move_dequeue_past_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
    },
    {
      "addr": 18446744071592612584,
      "name": "xhci_move_dequeue_past_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int xhci_move_dequeue_past_td(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td)
```

```json
{
  "name": "xhci_move_dequeue_past_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_move_dequeue_past_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:566",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590360064,
      "name": "xhci_move_dequeue_past_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1252
    },
    {
      "addr": 18446744071594495684,
      "name": "xhci_move_dequeue_past_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int xhci_move_dequeue_past_td(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td)
```

```json
{
  "name": "xhci_move_dequeue_past_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591992416,
      "name": "xhci_move_dequeue_past_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:566",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591992416,
      "name": "xhci_move_dequeue_past_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1399
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
int xhci_move_dequeue_past_td(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td)
```

```json
{
  "name": "xhci_move_dequeue_past_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592401552,
      "name": "xhci_move_dequeue_past_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:620",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592401552,
      "name": "xhci_move_dequeue_past_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1259
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
int xhci_move_dequeue_past_td(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td)
```

```json
{
  "name": "xhci_move_dequeue_past_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593146464,
      "name": "xhci_move_dequeue_past_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:628",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593146464,
      "name": "xhci_move_dequeue_past_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1282
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int xhci_move_dequeue_past_td(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td)
```
</details>
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

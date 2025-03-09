# Function: <code>xhci_map_temp_buffer</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int xhci_map_temp_buffer(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "xhci_map_temp_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588334256,
      "name": "xhci_map_temp_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:1270",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588334256,
      "name": "xhci_map_temp_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int xhci_map_temp_buffer(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "xhci_map_temp_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588216848,
      "name": "xhci_map_temp_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:1273",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216848,
      "name": "xhci_map_temp_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int xhci_map_temp_buffer(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "xhci_map_temp_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_map_temp_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:1282",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588859040,
      "name": "xhci_map_temp_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071592605703,
      "name": "xhci_map_temp_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int xhci_map_temp_buffer(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "xhci_map_temp_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_map_temp_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:1323",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590284960,
      "name": "xhci_map_temp_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    },
    {
      "addr": 18446744071594488804,
      "name": "xhci_map_temp_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int xhci_map_temp_buffer(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "xhci_map_temp_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_map_temp_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:1321",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591907664,
      "name": "xhci_map_temp_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    },
    {
      "addr": 18446744071596299905,
      "name": "xhci_map_temp_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int xhci_map_temp_buffer(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "xhci_map_temp_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_map_temp_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:1161",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592329840,
      "name": "xhci_map_temp_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    },
    {
      "addr": 18446744071596829570,
      "name": "xhci_map_temp_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int xhci_map_temp_buffer(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "xhci_map_temp_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_map_temp_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:1208",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593071248,
      "name": "xhci_map_temp_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    },
    {
      "addr": 18446744071597753221,
      "name": "xhci_map_temp_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int xhci_map_temp_buffer(struct usb_hcd * hcd, struct urb * urb)
```
</details>
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

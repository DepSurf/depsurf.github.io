# Function: <code>xhci_update_timeout_for_endpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585469821,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4471",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585865428,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4453",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586054276,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4446",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int xhci_update_timeout_for_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct usb_endpoint_descriptor * desc, enum usb3_link_state state, u16 * timeout)
```

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586112400,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4396",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586112400,
      "name": "xhci_update_timeout_for_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int xhci_update_timeout_for_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct usb_endpoint_descriptor * desc, enum usb3_link_state state, u16 * timeout)
```

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586556880,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4403",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586556880,
      "name": "xhci_update_timeout_for_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int xhci_update_timeout_for_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct usb_endpoint_descriptor * desc, enum usb3_link_state state, u16 * timeout)
```

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586820880,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4588",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586820880,
      "name": "xhci_update_timeout_for_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586994248,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4620",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587253598,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4665",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587454044,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4736",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588302312,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4746",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588337272,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4884",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588219912,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4811",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588864133,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4832",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590290695,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4859",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591913633,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4863",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592335818,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4704",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593077210,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4764",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500590712,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4736",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233051880,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4736",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293998512,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4736",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277461632,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4736",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587160076,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4736",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586918684,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4736",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587408604,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4736",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_update_timeout_for_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587515052,
      "name": "xhci_update_timeout_for_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:4736",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int xhci_update_timeout_for_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct usb_endpoint_descriptor * desc, enum usb3_link_state state, u16 * timeout)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int xhci_update_timeout_for_endpoint(struct xhci_hcd * xhci, struct usb_device * udev, struct usb_endpoint_descriptor * desc, enum usb3_link_state state, u16 * timeout)
```
</details>
</li>
</ul>

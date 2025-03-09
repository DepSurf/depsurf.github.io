# Function: <code>xhci_clear_hub_tt_buffer</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587305205,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587506421,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588357907,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1835",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588388227,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1840",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_clear_hub_tt_buffer(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_virt_ep * ep)
```

```json
{
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588263328,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2080",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263328,
      "name": "xhci_clear_hub_tt_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void xhci_clear_hub_tt_buffer(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_virt_ep * ep)
```

```json
{
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588914224,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2145",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588914224,
      "name": "xhci_clear_hub_tt_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void xhci_clear_hub_tt_buffer(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_virt_ep * ep)
```

```json
{
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590343904,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2079",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590343904,
      "name": "xhci_clear_hub_tt_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void xhci_clear_hub_tt_buffer(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_virt_ep * ep)
```

```json
{
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591973008,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2081",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591973008,
      "name": "xhci_clear_hub_tt_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void xhci_clear_hub_tt_buffer(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_virt_ep * ep)
```

```json
{
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592394064,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2103",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592394064,
      "name": "xhci_clear_hub_tt_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void xhci_clear_hub_tt_buffer(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_virt_ep * ep)
```

```json
{
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593137008,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2108",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593137008,
      "name": "xhci_clear_hub_tt_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500648164,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233107408,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294070004,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277512036,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587212453,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586971205,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587460981,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xhci_clear_hub_tt_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587568549,
      "name": "xhci_clear_hub_tt_buffer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1809",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void xhci_clear_hub_tt_buffer(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_virt_ep * ep)
```
</details>
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

# Function: <code>xhci_dbc_queue_trb</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586659826,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:217",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586923585,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:218",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587080581,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:218",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587344579,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:218",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587544513,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:217",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void xhci_dbc_queue_trb(struct xhci_ring * ring, u32 field1, u32 field2, u32 field3, u32 field4)
```

```json
{
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588407488,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:217",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407488,
      "name": "xhci_dbc_queue_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void xhci_dbc_queue_trb(struct xhci_ring * ring, u32 field1, u32 field2, u32 field3, u32 field4)
```

```json
{
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588437808,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:223",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588437808,
      "name": "xhci_dbc_queue_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588320952,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:223",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588978488,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:223",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590413404,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:223",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592049084,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:223",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592471788,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:223",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593213420,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:238",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500689468,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:217",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233144492,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:217",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294122452,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:217",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277546900,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:217",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587009297,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:217",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587499073,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:217",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
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
  "name": "xhci_dbc_queue_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587606801,
      "name": "xhci_dbc_queue_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:217",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void xhci_dbc_queue_trb(struct xhci_ring * ring, u32 field1, u32 field2, u32 field3, u32 field4)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void xhci_dbc_queue_trb(struct xhci_ring * ring, u32 field1, u32 field2, u32 field3, u32 field4)
```
</details>
</li>
</ul>

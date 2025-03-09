# Function: <code>xhci_dbc_free_req</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_dbc_free_req(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586661397,
      "name": "xhci_dbc_free_req",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:125",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663488,
      "name": "xhci_dbc_free_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586926128,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587083136,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587347856,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587549520,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588414477,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588444123,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:136",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588326827,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:136",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588983911,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:136",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590418339,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:136",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592056179,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:136",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592479011,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:136",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593223203,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:136",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500691888,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233150464,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294127008,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277549978,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587014304,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587504080,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests"
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
  "name": "xhci_dbc_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587612752,
      "name": "xhci_dbc_free_req",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:128",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void xhci_dbc_free_req(struct dbc_ep * dep, struct dbc_request * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void xhci_dbc_free_req(struct dbc_ep * dep, struct dbc_request * req)
```
</details>
</li>
</ul>

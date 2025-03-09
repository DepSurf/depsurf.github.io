# Function: <code>xhci_do_dbc_init</code>

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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586660425,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:824",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586924208,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:833",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587081216,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:834",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587345024,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:832",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587546800,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:831",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
int xhci_do_dbc_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588406560,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:831",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406560,
      "name": "xhci_do_dbc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int xhci_do_dbc_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588436880,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:927",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588436880,
      "name": "xhci_do_dbc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int xhci_do_dbc_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319872,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:927",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319872,
      "name": "xhci_do_dbc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int xhci_do_dbc_init(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588977408,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:927",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977408,
      "name": "xhci_do_dbc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500690324,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:831",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233147780,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:831",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294123404,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:831",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277547558,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:831",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587011584,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:831",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587501360,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:831",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
  "name": "xhci_do_dbc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587609232,
      "name": "xhci_do_dbc_init",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:831",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
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
int xhci_do_dbc_init(struct xhci_hcd * xhci)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int xhci_do_dbc_init(struct xhci_hcd * xhci)
```
</details>
</li>
</ul>

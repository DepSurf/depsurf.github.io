# Function: <code>xdbc_bulk_transfer</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```

```json
{
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587099968,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:463",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587099968,
      "name": "xdbc_bulk_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
int xdbc_bulk_transfer(void * data, int size, bool read)
```

```json
{
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587364816,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:463",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587364816,
      "name": "xdbc_bulk_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
int xdbc_bulk_transfer(void * data, int size, bool read)
```

```json
{
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587566656,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:463",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587566656,
      "name": "xdbc_bulk_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588426000,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:462",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_early_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588426000,
      "name": "xdbc_bulk_transfer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588456512,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:457",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_early_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456512,
      "name": "xdbc_bulk_transfer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588339040,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:457",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588339040,
      "name": "xdbc_bulk_transfer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588998016,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:464",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588998016,
      "name": "xdbc_bulk_transfer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590434352,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:464",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590434352,
      "name": "xdbc_bulk_transfer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592072912,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:464",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592072912,
      "name": "xdbc_bulk_transfer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592495840,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:464",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592495840,
      "name": "xdbc_bulk_transfer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593240224,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:464",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593240224,
      "name": "xdbc_bulk_transfer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```

```json
{
  "name": "xdbc_bulk_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587629120,
      "name": "xdbc_bulk_transfer",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:463",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587629120,
      "name": "xdbc_bulk_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int xdbc_bulk_transfer(void * data, int size, bool read)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

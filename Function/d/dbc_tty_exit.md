# Function: <code>dbc_tty_exit</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dbc_tty_exit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588444574,
      "name": "dbc_tty_exit",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:549",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_remove",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe"
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
  "name": "dbc_tty_exit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588327454,
      "name": "dbc_tty_exit",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:549",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_remove",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe"
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
  "name": "dbc_tty_exit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588985118,
      "name": "dbc_tty_exit",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgtty.c:547",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_remove",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void dbc_tty_exit()
```

```json
{
  "name": "dbc_tty_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590419792,
      "name": "dbc_tty_exit",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:573",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590419792,
      "name": "dbc_tty_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void dbc_tty_exit()
```

```json
{
  "name": "dbc_tty_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592057744,
      "name": "dbc_tty_exit",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:573",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592057744,
      "name": "dbc_tty_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void dbc_tty_exit()
```

```json
{
  "name": "dbc_tty_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592480576,
      "name": "dbc_tty_exit",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:573",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592480576,
      "name": "dbc_tty_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void dbc_tty_exit()
```

```json
{
  "name": "dbc_tty_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593224816,
      "name": "dbc_tty_exit",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:572",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593224816,
      "name": "dbc_tty_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void dbc_tty_exit()
```
</details>
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

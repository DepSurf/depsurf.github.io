# Function: <code>xdbc_early_setup</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604972399,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:555",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
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
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605081518,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:553",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
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
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605121001,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:553",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
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
int xdbc_early_setup()
```

```json
{
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609396628,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:552",
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
      "addr": 18446744071609396628,
      "name": "xdbc_early_setup",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 255
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
int xdbc_early_setup()
```

```json
{
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612468109,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:547",
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
      "addr": 18446744071612468109,
      "name": "xdbc_early_setup",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 262
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
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614610849,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:547",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
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
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615568344,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:554",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
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
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617375006,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:554",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
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
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628114552,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:554",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
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
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619881080,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:553",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
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
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622190760,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:553",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdbc_early_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605125195,
      "name": "xdbc_early_setup",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:553",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
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
int xdbc_early_setup()
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
int xdbc_early_setup()
```
</details>
</li>
</ul>

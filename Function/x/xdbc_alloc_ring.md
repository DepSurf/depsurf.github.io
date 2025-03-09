# Function: <code>xdbc_alloc_ring</code>

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
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604972639,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:176",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
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
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605081760,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:176",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
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
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605121243,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:176",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
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
int xdbc_alloc_ring(struct xdbc_segment * seg, struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609396572,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:175",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_early_setup",
        "drivers/usb/early/xhci-dbc.c:xdbc_early_setup",
        "drivers/usb/early/xhci-dbc.c:xdbc_early_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609396572,
      "name": "xdbc_alloc_ring",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 56
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
int xdbc_alloc_ring(struct xdbc_segment * seg, struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612467709,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:170",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_early_setup",
        "drivers/usb/early/xhci-dbc.c:xdbc_early_setup",
        "drivers/usb/early/xhci-dbc.c:xdbc_early_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612467709,
      "name": "xdbc_alloc_ring",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 56
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
int xdbc_alloc_ring(struct xdbc_segment * seg, struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614609690,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:170",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614609690,
      "name": "xdbc_alloc_ring",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 56
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
int xdbc_alloc_ring(struct xdbc_segment * seg, struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615567209,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:177",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615567209,
      "name": "xdbc_alloc_ring",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int xdbc_alloc_ring(struct xdbc_segment * seg, struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617373874,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:177",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617373874,
      "name": "xdbc_alloc_ring",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628114787,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:177",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
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
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619881315,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:177",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
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
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622190995,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:177",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
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
  "name": "xdbc_alloc_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605125437,
      "name": "xdbc_alloc_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:176",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
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
int xdbc_alloc_ring(struct xdbc_segment * seg, struct xdbc_ring * ring)
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int xdbc_alloc_ring(struct xdbc_segment * seg, struct xdbc_ring * ring)
```
</details>
</li>
</ul>

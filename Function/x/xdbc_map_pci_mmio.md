# Function: <code>xdbc_map_pci_mmio</code>

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
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604971604,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:38",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
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
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605080725,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:38",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
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
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605120208,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:38",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
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
void * xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func)
```

```json
{
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609395475,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:37",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609395475,
      "name": "xdbc_map_pci_mmio",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 431
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
void * xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func)
```

```json
{
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612466956,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:39",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612466956,
      "name": "xdbc_map_pci_mmio",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 431
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
void * xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func)
```

```json
{
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614609127,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:39",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614609127,
      "name": "xdbc_map_pci_mmio",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 431
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
void * xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func)
```

```json
{
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615566618,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:38",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615566618,
      "name": "xdbc_map_pci_mmio",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 459
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
void * xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func)
```

```json
{
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617373243,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:38",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617373243,
      "name": "xdbc_map_pci_mmio",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 471
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
void * xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func)
```

```json
{
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628112736,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:38",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628112736,
      "name": "xdbc_map_pci_mmio",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 539
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
void * xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func)
```

```json
{
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619879264,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:38",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619879264,
      "name": "xdbc_map_pci_mmio",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 539
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
void * xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func)
```

```json
{
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622188944,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:38",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622188944,
      "name": "xdbc_map_pci_mmio",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 539
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdbc_map_pci_mmio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605124402,
      "name": "xdbc_map_pci_mmio",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:38",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
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
void * xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

# Function: <code>__dw_pcie_ep_find_next_cap</code>

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
  "name": "__dw_pcie_ep_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__dw_pcie_ep_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:43",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dw_pcie_ep_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__dw_pcie_ep_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:43",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u8 __dw_pcie_ep_find_next_cap(struct dw_pcie_ep * ep, u8 func_no, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_ep_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585645824,
      "name": "__dw_pcie_ep_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:87",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645824,
      "name": "__dw_pcie_ep_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
u8 __dw_pcie_ep_find_next_cap(struct dw_pcie_ep * ep, u8 func_no, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_ep_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585526640,
      "name": "__dw_pcie_ep_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:87",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585526640,
      "name": "__dw_pcie_ep_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
u8 __dw_pcie_ep_find_next_cap(struct dw_pcie_ep * ep, u8 func_no, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_ep_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585996608,
      "name": "__dw_pcie_ep_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:87",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585996608,
      "name": "__dw_pcie_ep_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
u8 __dw_pcie_ep_find_next_cap(struct dw_pcie_ep * ep, u8 func_no, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_ep_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587213488,
      "name": "__dw_pcie_ep_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:88",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587213488,
      "name": "__dw_pcie_ep_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
u8 __dw_pcie_ep_find_next_cap(struct dw_pcie_ep * ep, u8 func_no, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_ep_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588445232,
      "name": "__dw_pcie_ep_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:86",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588445232,
      "name": "__dw_pcie_ep_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
u8 __dw_pcie_ep_find_next_cap(struct dw_pcie_ep * ep, u8 func_no, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_ep_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588724272,
      "name": "__dw_pcie_ep_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:86",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588724272,
      "name": "__dw_pcie_ep_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
u8 __dw_pcie_ep_find_next_cap(struct dw_pcie_ep * ep, u8 func_no, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_ep_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589028887,
      "name": "__dw_pcie_ep_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:75",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589027392,
      "name": "__dw_pcie_ep_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
u8 __dw_pcie_ep_find_next_cap(struct dw_pcie_ep * ep, u8 func_no, u8 cap_ptr, u8 cap)
```
</details>
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

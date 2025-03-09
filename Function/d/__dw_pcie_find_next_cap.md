# Function: <code>__dw_pcie_find_next_cap</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584812848,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812848,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585507270,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:23",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506928,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585640130,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:24",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639968,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585519890,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:24",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519728,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585989506,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:24",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989344,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587205587,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:24",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587205424,
      "name": "__dw_pcie_find_next_cap",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588434370,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:196",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433920,
      "name": "__dw_pcie_find_next_cap",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588712210,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:209",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588711760,
      "name": "__dw_pcie_find_next_cap",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589013299,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:209",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589013120,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497155976,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497155976,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230361464,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230361464,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275740514,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275740514,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584761584,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584761584,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584692368,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692368,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584763008,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763008,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```

```json
{
  "name": "__dw_pcie_find_next_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584870528,
      "name": "__dw_pcie_find_next_cap",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:22",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870528,
      "name": "__dw_pcie_find_next_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie * pci, u8 cap_ptr, u8 cap)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

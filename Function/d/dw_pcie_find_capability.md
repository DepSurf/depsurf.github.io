# Function: <code>dw_pcie_find_capability</code>

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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584812944,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:44",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812944,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585507237,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:45",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507056,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585640096,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:46",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640096,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585519856,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:46",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519856,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585989472,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:46",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989472,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587205552,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:46",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587205552,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588434352,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:218",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434064,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588712192,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:231",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588711904,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589013264,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:231",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589013264,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497156120,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:44",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497156120,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230361564,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:44",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230361564,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275740628,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:44",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275740628,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584761680,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:44",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584761680,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584692464,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:44",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692464,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584763104,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:44",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763104,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
```

```json
{
  "name": "dw_pcie_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584870624,
      "name": "dw_pcie_find_capability",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:44",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870624,
      "name": "dw_pcie_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
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
u8 dw_pcie_find_capability(struct dw_pcie * pci, u8 cap)
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

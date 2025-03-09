# Function: <code>dw_pcie_readl_atu</code>

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
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584478137,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:307",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584676238,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:319",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584814846,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:331",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585509230,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:345",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie * pci, u32 reg)
```

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591419261,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:184",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638336,
      "name": "dw_pcie_readl_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071591419261,
      "name": "dw_pcie_readl_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie * pci, u32 reg)
```

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585518344,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:184",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585518288,
      "name": "dw_pcie_readl_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071591361714,
      "name": "dw_pcie_readl_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie * pci, u32 reg)
```

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585987960,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:184",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585987904,
      "name": "dw_pcie_readl_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071592391431,
      "name": "dw_pcie_readl_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie * pci, u32 reg)
```

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587203784,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:184",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587203712,
      "name": "dw_pcie_readl_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071594256149,
      "name": "dw_pcie_readl_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
u32 dw_pcie_readl_atu(struct dw_pcie * pci, u32 dir, u32 index, u32 reg)
```

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588432768,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:366",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432768,
      "name": "dw_pcie_readl_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
u32 dw_pcie_readl_atu(struct dw_pcie * pci, u32 dir, u32 index, u32 reg)
```

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588710608,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:379",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710608,
      "name": "dw_pcie_readl_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
u32 dw_pcie_readl_atu(struct dw_pcie * pci, u32 dir, u32 index, u32 reg)
```

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589011728,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:380",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589011728,
      "name": "dw_pcie_readl_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497158224,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:331",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230363556,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:331",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275742434,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:331",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584763582,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:331",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584694366,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:331",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584765006,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:331",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
  "name": "dw_pcie_readl_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584872526,
      "name": "dw_pcie_readl_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware.h:331",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie * pci, u32 reg)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 dir</code>
</li>
<li>
<b>Param added. </b>
<code>u32 index</code>
</li>
<li>
<b>Param reordered. </b>
<code>pci, reg</code> ➡️ <code>pci, dir, index, reg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

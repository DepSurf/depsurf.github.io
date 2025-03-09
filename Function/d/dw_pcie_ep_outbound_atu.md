# Function: <code>dw_pcie_ep_outbound_atu</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584390097,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:95",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584481600,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:128",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584481600,
      "name": "dw_pcie_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:128",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679344,
      "name": "dw_pcie_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584680502,
      "name": "dw_pcie_ep_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:95",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584817888,
      "name": "dw_pcie_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584819046,
      "name": "dw_pcie_ep_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:104",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585512704,
      "name": "dw_pcie_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585514088,
      "name": "dw_pcie_ep_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585646920,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
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
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585527736,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
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
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585997736,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
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
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587214747,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:184",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
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
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588446891,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:185",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
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
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588725970,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:185",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
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
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589026466,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:163",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497165720,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:95",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
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
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230370188,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:95",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
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
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275748448,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:95",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:95",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584766624,
      "name": "dw_pcie_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584767782,
      "name": "dw_pcie_ep_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:95",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584697408,
      "name": "dw_pcie_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584698566,
      "name": "dw_pcie_ep_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:95",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584768048,
      "name": "dw_pcie_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584769206,
      "name": "dw_pcie_ep_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_outbound_atu",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:95",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584875568,
      "name": "dw_pcie_ep_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584876726,
      "name": "dw_pcie_ep_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
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
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int dw_pcie_ep_outbound_atu(struct dw_pcie_ep * ep, phys_addr_t phys_addr, u64 pci_addr, size_t size)
```
</details>
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

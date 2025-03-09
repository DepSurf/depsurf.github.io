# Function: <code>dw_pcie_ep_map_addr</code>

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
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584390097,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:197",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584482678,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:230",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584680274,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:230",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584818818,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:197",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585513832,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:208",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:295",
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
      "addr": 18446744071585646880,
      "name": "dw_pcie_ep_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071591420633,
      "name": "dw_pcie_ep_map_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:295",
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
      "addr": 18446744071585527696,
      "name": "dw_pcie_ep_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071591362236,
      "name": "dw_pcie_ep_map_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, u8 vfunc_no, phys_addr_t addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:295",
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
      "addr": 18446744071585997696,
      "name": "dw_pcie_ep_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071592391974,
      "name": "dw_pcie_ep_map_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, u8 vfunc_no, phys_addr_t addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:296",
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
      "addr": 18446744071587214704,
      "name": "dw_pcie_ep_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071594256705,
      "name": "dw_pcie_ep_map_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, u8 vfunc_no, phys_addr_t addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588446848,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:302",
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
      "addr": 18446744071588446848,
      "name": "dw_pcie_ep_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, u8 vfunc_no, phys_addr_t addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588725936,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:302",
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
      "addr": 18446744071588725936,
      "name": "dw_pcie_ep_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, u8 vfunc_no, phys_addr_t addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589026432,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:277",
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
      "addr": 18446744071589026432,
      "name": "dw_pcie_ep_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497165672,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:197",
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
      "addr": 18446603336497165672,
      "name": "dw_pcie_ep_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230370160,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:197",
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
      "addr": 3230370160,
      "name": "dw_pcie_ep_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size)
```

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275748404,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:197",
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
      "addr": 18446743936275748404,
      "name": "dw_pcie_ep_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584767554,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:197",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584698338,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:197",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584768978,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:197",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_ep_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584876498,
      "name": "dw_pcie_ep_map_addr",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:197",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 vfunc_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>epc, func_no, addr, pci_addr, size</code> ➡️ <code>epc, func_no, vfunc_no, addr, pci_addr, size</code>
</li>
</ul>
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc * epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size)
```
</details>
</li>
</ul>

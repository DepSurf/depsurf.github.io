# Function: <code>pci_epc_mem_init</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t phys_base, size_t size)
```

```json
{
  "name": "pci_epc_mem_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583903200,
      "name": "pci_epc_mem_init",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-mem.c:35",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903200,
      "name": "pci_epc_mem_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t base, size_t size, size_t page_size)
```

```json
{
  "name": "pci_epc_mem_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585506112,
      "name": "pci_epc_mem_init",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-mem.c:118",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506112,
      "name": "pci_epc_mem_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t base, size_t size, size_t page_size)
```

```json
{
  "name": "pci_epc_mem_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585637808,
      "name": "pci_epc_mem_init",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-mem.c:118",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585637808,
      "name": "pci_epc_mem_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t base, size_t size, size_t page_size)
```

```json
{
  "name": "pci_epc_mem_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585517744,
      "name": "pci_epc_mem_init",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-mem.c:118",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517744,
      "name": "pci_epc_mem_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t base, size_t size, size_t page_size)
```

```json
{
  "name": "pci_epc_mem_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585987312,
      "name": "pci_epc_mem_init",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-mem.c:118",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585987312,
      "name": "pci_epc_mem_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t base, size_t size, size_t page_size)
```

```json
{
  "name": "pci_epc_mem_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587203392,
      "name": "pci_epc_mem_init",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-mem.c:118",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587203392,
      "name": "pci_epc_mem_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t base, size_t size, size_t page_size)
```

```json
{
  "name": "pci_epc_mem_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588431616,
      "name": "pci_epc_mem_init",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-mem.c:118",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588431616,
      "name": "pci_epc_mem_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t base, size_t size, size_t page_size)
```

```json
{
  "name": "pci_epc_mem_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588709280,
      "name": "pci_epc_mem_init",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-mem.c:118",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588709280,
      "name": "pci_epc_mem_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t base, size_t size, size_t page_size)
```

```json
{
  "name": "pci_epc_mem_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589010128,
      "name": "pci_epc_mem_init",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-mem.c:128",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589010128,
      "name": "pci_epc_mem_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t phys_base, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t phys_base, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int pci_epc_mem_init(struct pci_epc * epc, phys_addr_t base, size_t size, size_t page_size)
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

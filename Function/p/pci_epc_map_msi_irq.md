# Function: <code>pci_epc_map_msi_irq</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_epc_map_msi_irq(struct pci_epc * epc, u8 func_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 * msi_data, u32 * msi_addr_offset)
```

```json
{
  "name": "pci_epc_map_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585511184,
      "name": "pci_epc_map_msi_irq",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:253",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511184,
      "name": "pci_epc_map_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int pci_epc_map_msi_irq(struct pci_epc * epc, u8 func_no, u8 vfunc_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 * msi_data, u32 * msi_addr_offset)
```

```json
{
  "name": "pci_epc_map_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585979344,
      "name": "pci_epc_map_msi_irq",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:263",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979344,
      "name": "pci_epc_map_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int pci_epc_map_msi_irq(struct pci_epc * epc, u8 func_no, u8 vfunc_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 * msi_data, u32 * msi_addr_offset)
```

```json
{
  "name": "pci_epc_map_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587194336,
      "name": "pci_epc_map_msi_irq",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:263",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587194336,
      "name": "pci_epc_map_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int pci_epc_map_msi_irq(struct pci_epc * epc, u8 func_no, u8 vfunc_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 * msi_data, u32 * msi_addr_offset)
```

```json
{
  "name": "pci_epc_map_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588421728,
      "name": "pci_epc_map_msi_irq",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:263",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421728,
      "name": "pci_epc_map_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int pci_epc_map_msi_irq(struct pci_epc * epc, u8 func_no, u8 vfunc_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 * msi_data, u32 * msi_addr_offset)
```

```json
{
  "name": "pci_epc_map_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588698816,
      "name": "pci_epc_map_msi_irq",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:263",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588698816,
      "name": "pci_epc_map_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int pci_epc_map_msi_irq(struct pci_epc * epc, u8 func_no, u8 vfunc_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 * msi_data, u32 * msi_addr_offset)
```

```json
{
  "name": "pci_epc_map_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588999632,
      "name": "pci_epc_map_msi_irq",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:262",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588999632,
      "name": "pci_epc_map_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int pci_epc_map_msi_irq(struct pci_epc * epc, u8 func_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 * msi_data, u32 * msi_addr_offset)
```
</details>
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
<code>epc, func_no, phys_addr, interrupt_num, entry_size, msi_data, msi_addr_offset</code> ➡️ <code>epc, func_no, vfunc_no, phys_addr, interrupt_num, entry_size, msi_data, msi_addr_offset</code>
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

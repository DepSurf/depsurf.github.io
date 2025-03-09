# Function: <code>pci_irqd_intx_xlate</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate ❓</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain * d, struct device_node * node, const u32 * intspec, unsigned int intsize, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "pci_irqd_intx_xlate",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497115816,
      "name": "pci_irqd_intx_xlate",
      "external": false,
      "loc": "include/linux/pci.h:1523",
      "file": "drivers/pci/controller/pcie-xilinx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497118872,
      "name": "pci_irqd_intx_xlate",
      "external": false,
      "loc": "include/linux/pci.h:1523",
      "file": "drivers/pci/controller/pcie-xilinx-nwl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497129888,
      "name": "pci_irqd_intx_xlate",
      "external": false,
      "loc": "include/linux/pci.h:1523",
      "file": "drivers/pci/controller/pcie-altera.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497115816,
      "name": "pci_irqd_intx_xlate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336497118872,
      "name": "pci_irqd_intx_xlate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336497129888,
      "name": "pci_irqd_intx_xlate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate ❓</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain * d, struct device_node * node, const u32 * intspec, unsigned int intsize, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "pci_irqd_intx_xlate",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230334724,
      "name": "pci_irqd_intx_xlate",
      "external": false,
      "loc": "include/linux/pci.h:1523",
      "file": "drivers/pci/controller/pcie-xilinx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230341824,
      "name": "pci_irqd_intx_xlate",
      "external": false,
      "loc": "include/linux/pci.h:1523",
      "file": "drivers/pci/controller/pcie-altera.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230374508,
      "name": "pci_irqd_intx_xlate",
      "external": false,
      "loc": "include/linux/pci.h:1523",
      "file": "drivers/pci/controller/dwc/pci-dra7xx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230334724,
      "name": "pci_irqd_intx_xlate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 3230341824,
      "name": "pci_irqd_intx_xlate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 3230374508,
      "name": "pci_irqd_intx_xlate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain * d, struct device_node * node, const u32 * intspec, unsigned int intsize, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "pci_irqd_intx_xlate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291148848,
      "name": "pci_irqd_intx_xlate",
      "external": false,
      "loc": "include/linux/pci.h:1523",
      "file": "drivers/pci/controller/pcie-xilinx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291148848,
      "name": "pci_irqd_intx_xlate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain * d, struct device_node * node, const u32 * intspec, unsigned int intsize, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "pci_irqd_intx_xlate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275737232,
      "name": "pci_irqd_intx_xlate",
      "external": false,
      "loc": "include/linux/pci.h:1523",
      "file": "drivers/pci/controller/pcie-xilinx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275737232,
      "name": "pci_irqd_intx_xlate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain * d, struct device_node * node, const u32 * intspec, unsigned int intsize, long unsigned int * out_hwirq, unsigned int * out_type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain * d, struct device_node * node, const u32 * intspec, unsigned int intsize, long unsigned int * out_hwirq, unsigned int * out_type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain * d, struct device_node * node, const u32 * intspec, unsigned int intsize, long unsigned int * out_hwirq, unsigned int * out_type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain * d, struct device_node * node, const u32 * intspec, unsigned int intsize, long unsigned int * out_hwirq, unsigned int * out_type)
```
</details>
</li>
</ul>

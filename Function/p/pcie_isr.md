# Function: <code>pcie_isr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
irqreturn_t pcie_isr(int irq, void * dev_id)
```

```json
{
  "name": "pcie_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368528,
      "name": "pcie_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:538",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368528,
      "name": "pcie_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
irqreturn_t pcie_isr(int irq, void * dev_id)
```

```json
{
  "name": "pcie_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681824,
      "name": "pcie_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:538",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681824,
      "name": "pcie_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 931
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
irqreturn_t pcie_isr(int irq, void * dev_id)
```

```json
{
  "name": "pcie_isr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583820895,
      "name": "pcie_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:652",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820832,
      "name": "pcie_isr",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
irqreturn_t pcie_isr(int irq, void * dev_id)
```

```json
{
  "name": "pcie_isr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583863791,
      "name": "pcie_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:660",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863728,
      "name": "pcie_isr",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
irqreturn_t pcie_isr(int irq, void * dev_id)
```

```json
{
  "name": "pcie_isr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584127427,
      "name": "pcie_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:657",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127360,
      "name": "pcie_isr",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
irqreturn_t pcie_isr(int irq, void * dev_id)
```

```json
{
  "name": "pcie_isr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584328115,
      "name": "pcie_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:630",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584328048,
      "name": "pcie_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
irqreturn_t pcie_isr(int irq, void * dev_id)
```
</details>
</li>
</ul>

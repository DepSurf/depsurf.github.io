# Function: <code>pcie_port_enable_irq_vec</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583830409,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:55",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584093625,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:103",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584285603,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:100",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584381027,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:100",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584577893,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584714981,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int pcie_port_enable_irq_vec(struct pci_dev * dev, int * irqs, int mask)
```

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585367760,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585367760,
      "name": "pcie_port_enable_irq_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int pcie_port_enable_irq_vec(struct pci_dev * dev, int * irqs, int mask)
```

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585526240,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585526240,
      "name": "pcie_port_enable_irq_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
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
int pcie_port_enable_irq_vec(struct pci_dev * dev, int * irqs, int mask)
```

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585404624,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585404624,
      "name": "pcie_port_enable_irq_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int pcie_port_enable_irq_vec(struct pci_dev * dev, int * irqs, int mask)
```

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585866096,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585866096,
      "name": "pcie_port_enable_irq_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int pcie_port_enable_irq_vec(struct pci_dev * dev, int * irqs, int mask)
```

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587061344,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587061344,
      "name": "pcie_port_enable_irq_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
int pcie_port_enable_irq_vec(struct pci_dev * dev, int * irqs, int mask)
```

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588247184,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv.c:112",
      "file": "drivers/pci/pcie/portdrv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588247184,
      "name": "pcie_port_enable_irq_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int pcie_port_enable_irq_vec(struct pci_dev * dev, int * irqs, int mask)
```

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588522192,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv.c:112",
      "file": "drivers/pci/pcie/portdrv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588522192,
      "name": "pcie_port_enable_irq_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int pcie_port_enable_irq_vec(struct pci_dev * dev, int * irqs, int mask)
```

```json
{
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588820784,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv.c:113",
      "file": "drivers/pci/pcie/portdrv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588820784,
      "name": "pcie_port_enable_irq_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496973740,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230237992,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275642166,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584665461,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584594613,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584665141,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
  "name": "pcie_port_enable_irq_vec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584772837,
      "name": "pcie_port_enable_irq_vec",
      "external": false,
      "loc": "drivers/pci/pcie/portdrv_core.c:101",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int pcie_port_enable_irq_vec(struct pci_dev * dev, int * irqs, int mask)
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

# Function: <code>pcie_pme_disable_interrupt</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597344,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:368",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597344,
      "name": "pcie_pme_disable_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584735168,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:368",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735168,
      "name": "pcie_pme_disable_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585389449,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:368",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585546777,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:376",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
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
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585425033,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:376",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
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
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585889929,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:376",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
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
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587086793,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:376",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
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
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588274361,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:376",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
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
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588549993,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:376",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
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
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588849609,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:378",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496995896,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:368",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496995896,
      "name": "pcie_pme_disable_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230255996,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:368",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230255996,
      "name": "pcie_pme_disable_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275659744,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:368",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275659744,
      "name": "pcie_pme_disable_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584683968,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:368",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584683968,
      "name": "pcie_pme_disable_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584614048,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:368",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614048,
      "name": "pcie_pme_disable_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584685328,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:368",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584685328,
      "name": "pcie_pme_disable_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```

```json
{
  "name": "pcie_pme_disable_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584791504,
      "name": "pcie_pme_disable_interrupt",
      "external": false,
      "loc": "drivers/pci/pcie/pme.c:368",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584791504,
      "name": "pcie_pme_disable_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
```
</details>
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
void pcie_pme_disable_interrupt(struct pci_dev * port, struct pcie_pme_service_data * data)
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

# Function: <code>pcibios_get_phb_of_node</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct device_node * pcibios_get_phb_of_node(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_get_phb_of_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496946248,
      "name": "pcibios_get_phb_of_node",
      "external": true,
      "loc": "drivers/pci/of.c:61",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_set_bus_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496946248,
      "name": "pcibios_get_phb_of_node",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 104
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
struct device_node * pcibios_get_phb_of_node(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_get_phb_of_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230212788,
      "name": "pcibios_get_phb_of_node",
      "external": true,
      "loc": "drivers/pci/of.c:61",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_set_bus_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230212788,
      "name": "pcibios_get_phb_of_node",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 124
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
struct device_node * pcibios_get_phb_of_node(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_get_phb_of_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282616784,
      "name": "pcibios_get_phb_of_node",
      "external": true,
      "loc": "arch/powerpc/kernel/pci-common.c:1583",
      "file": "arch/powerpc/kernel/pci-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/pci.c:pseries_root_bridge_prepare",
        "drivers/pci/of.c:pci_set_bus_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282616784,
      "name": "pcibios_get_phb_of_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct device_node * pcibios_get_phb_of_node(struct pci_bus * bus)
```

```json
{
  "name": "pcibios_get_phb_of_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275619616,
      "name": "pcibios_get_phb_of_node",
      "external": true,
      "loc": "drivers/pci/of.c:61",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_set_bus_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275619616,
      "name": "pcibios_get_phb_of_node",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 82
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
struct device_node * pcibios_get_phb_of_node(struct pci_bus * bus)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * pcibios_get_phb_of_node(struct pci_bus * bus)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct device_node * pcibios_get_phb_of_node(struct pci_bus * bus)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct device_node * pcibios_get_phb_of_node(struct pci_bus * bus)
```
</details>
</li>
</ul>

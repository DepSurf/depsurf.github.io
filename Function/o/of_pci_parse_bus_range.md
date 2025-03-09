# Function: <code>of_pci_parse_bus_range</code>

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
int of_pci_parse_bus_range(struct device_node * node, struct resource * res)
```

```json
{
  "name": "of_pci_parse_bus_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496944360,
      "name": "of_pci_parse_bus_range",
      "external": true,
      "loc": "drivers/pci/of.c:173",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:devm_of_pci_get_host_bridge_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496944360,
      "name": "of_pci_parse_bus_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int of_pci_parse_bus_range(struct device_node * node, struct resource * res)
```

```json
{
  "name": "of_pci_parse_bus_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230210748,
      "name": "of_pci_parse_bus_range",
      "external": true,
      "loc": "drivers/pci/of.c:173",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:devm_of_pci_get_host_bridge_resources",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_parse_dt",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230210748,
      "name": "of_pci_parse_bus_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int of_pci_parse_bus_range(struct device_node * node, struct resource * res)
```

```json
{
  "name": "of_pci_parse_bus_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291038704,
      "name": "of_pci_parse_bus_range",
      "external": true,
      "loc": "drivers/pci/of.c:173",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:devm_of_pci_get_host_bridge_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291038704,
      "name": "of_pci_parse_bus_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int of_pci_parse_bus_range(struct device_node * node, struct resource * res)
```

```json
{
  "name": "of_pci_parse_bus_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275618080,
      "name": "of_pci_parse_bus_range",
      "external": true,
      "loc": "drivers/pci/of.c:173",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:devm_of_pci_get_host_bridge_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275618080,
      "name": "of_pci_parse_bus_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int of_pci_parse_bus_range(struct device_node * node, struct resource * res)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_pci_parse_bus_range(struct device_node * node, struct resource * res)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_pci_parse_bus_range(struct device_node * node, struct resource * res)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_pci_parse_bus_range(struct device_node * node, struct resource * res)
```
</details>
</li>
</ul>

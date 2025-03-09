# Function: <code>cdns_pcie_enable_phy</code>

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
int cdns_pcie_enable_phy(struct cdns_pcie * pcie)
```

```json
{
  "name": "cdns_pcie_enable_phy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497091392,
      "name": "cdns_pcie_enable_phy",
      "external": true,
      "loc": "drivers/pci/controller/pcie-cadence.c:138",
      "file": "drivers/pci/controller/pcie-cadence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_resume_noirq",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497091392,
      "name": "cdns_pcie_enable_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int cdns_pcie_enable_phy(struct cdns_pcie * pcie)
```

```json
{
  "name": "cdns_pcie_enable_phy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230295016,
      "name": "cdns_pcie_enable_phy",
      "external": true,
      "loc": "drivers/pci/controller/pcie-cadence.c:138",
      "file": "drivers/pci/controller/pcie-cadence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_resume_noirq",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230295016,
      "name": "cdns_pcie_enable_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int cdns_pcie_enable_phy(struct cdns_pcie * pcie)
```

```json
{
  "name": "cdns_pcie_enable_phy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291134080,
      "name": "cdns_pcie_enable_phy",
      "external": true,
      "loc": "drivers/pci/controller/pcie-cadence.c:138",
      "file": "drivers/pci/controller/pcie-cadence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_resume_noirq",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291134080,
      "name": "cdns_pcie_enable_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int cdns_pcie_enable_phy(struct cdns_pcie * pcie)
```

```json
{
  "name": "cdns_pcie_enable_phy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275726714,
      "name": "cdns_pcie_enable_phy",
      "external": true,
      "loc": "drivers/pci/controller/pcie-cadence.c:138",
      "file": "drivers/pci/controller/pcie-cadence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275726714,
      "name": "cdns_pcie_enable_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int cdns_pcie_enable_phy(struct cdns_pcie * pcie)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int cdns_pcie_enable_phy(struct cdns_pcie * pcie)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int cdns_pcie_enable_phy(struct cdns_pcie * pcie)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int cdns_pcie_enable_phy(struct cdns_pcie * pcie)
```
</details>
</li>
</ul>

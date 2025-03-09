# Function: <code>of_pci_range_parser_one</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_pci_range_parser_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_pci_range_parser_one",
      "external": false,
      "loc": "include/linux/of_address.h:101",
      "file": "drivers/firmware/efi/sysfb_efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "of_pci_range_parser_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_pci_range_parser_one",
      "external": false,
      "loc": "include/linux/of_address.h:101",
      "file": "drivers/firmware/efi/sysfb_efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "of_pci_range_parser_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_pci_range_parser_one",
      "external": false,
      "loc": "include/linux/of_address.h:101",
      "file": "drivers/firmware/efi/sysfb_efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "of_pci_range_parser_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_pci_range_parser_one",
      "external": false,
      "loc": "include/linux/of_address.h:128",
      "file": "drivers/firmware/efi/sysfb_efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "of_pci_range_parser_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_pci_range_parser_one",
      "external": false,
      "loc": "include/linux/of_address.h:128",
      "file": "drivers/firmware/efi/sysfb_efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
struct of_pci_range * of_pci_range_parser_one(struct of_pci_range_parser * parser, struct of_pci_range * range)
```

```json
{
  "name": "of_pci_range_parser_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501641048,
      "name": "of_pci_range_parser_one",
      "external": true,
      "loc": "drivers/of/address.c:268",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:devm_of_pci_get_host_bridge_resources",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501641048,
      "name": "of_pci_range_parser_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
struct of_pci_range * of_pci_range_parser_one(struct of_pci_range_parser * parser, struct of_pci_range * range)
```

```json
{
  "name": "of_pci_range_parser_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234160044,
      "name": "of_pci_range_parser_one",
      "external": true,
      "loc": "drivers/of/address.c:268",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:devm_of_pci_get_host_bridge_resources",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_parse_dt",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_parse_map_dma_ranges",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_parse_map_dma_ranges",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234160044,
      "name": "of_pci_range_parser_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct of_pci_range * of_pci_range_parser_one(struct of_pci_range_parser * parser, struct of_pci_range * range)
```

```json
{
  "name": "of_pci_range_parser_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295076544,
      "name": "of_pci_range_parser_one",
      "external": true,
      "loc": "drivers/of/address.c:268",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pci_process_bridge_OF_ranges",
        "drivers/pci/of.c:devm_of_pci_get_host_bridge_resources",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295076544,
      "name": "of_pci_range_parser_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
struct of_pci_range * of_pci_range_parser_one(struct of_pci_range_parser * parser, struct of_pci_range * range)
```

```json
{
  "name": "of_pci_range_parser_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278100146,
      "name": "of_pci_range_parser_one",
      "external": true,
      "loc": "drivers/of/address.c:268",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:devm_of_pci_get_host_bridge_resources",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278100146,
      "name": "of_pci_range_parser_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
struct of_pci_range * of_pci_range_parser_one(struct of_pci_range_parser * parser, struct of_pci_range * range)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct of_pci_range * of_pci_range_parser_one(struct of_pci_range_parser * parser, struct of_pci_range * range)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct of_pci_range * of_pci_range_parser_one(struct of_pci_range_parser * parser, struct of_pci_range * range)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct of_pci_range * of_pci_range_parser_one(struct of_pci_range_parser * parser, struct of_pci_range * range)
```
</details>
</li>
</ul>

# Function: <code>pci_host_common_probe</code>

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
int pci_host_common_probe(struct platform_device * pdev, struct pci_ecam_ops * ops)
```

```json
{
  "name": "pci_host_common_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497115064,
      "name": "pci_host_common_probe",
      "external": true,
      "loc": "drivers/pci/controller/pci-host-common.c:57",
      "file": "drivers/pci/controller/pci-host-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pci-host-generic.c:gen_pci_probe",
        "drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_almost_ecam_probe",
        "drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_probe",
        "drivers/pci/controller/pci-thunder-pem.c:thunder_pem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497115064,
      "name": "pci_host_common_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int pci_host_common_probe(struct platform_device * pdev, struct pci_ecam_ops * ops)
```

```json
{
  "name": "pci_host_common_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230334064,
      "name": "pci_host_common_probe",
      "external": true,
      "loc": "drivers/pci/controller/pci-host-common.c:57",
      "file": "drivers/pci/controller/pci-host-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pci-host-generic.c:gen_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230334064,
      "name": "pci_host_common_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int pci_host_common_probe(struct platform_device * pdev, struct pci_ecam_ops * ops)
```

```json
{
  "name": "pci_host_common_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291147888,
      "name": "pci_host_common_probe",
      "external": true,
      "loc": "drivers/pci/controller/pci-host-common.c:57",
      "file": "drivers/pci/controller/pci-host-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pci-host-generic.c:gen_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291147888,
      "name": "pci_host_common_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int pci_host_common_probe(struct platform_device * pdev, struct pci_ecam_ops * ops)
```

```json
{
  "name": "pci_host_common_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275736600,
      "name": "pci_host_common_probe",
      "external": true,
      "loc": "drivers/pci/controller/pci-host-common.c:57",
      "file": "drivers/pci/controller/pci-host-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pci-host-generic.c:gen_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275736600,
      "name": "pci_host_common_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int pci_host_common_probe(struct platform_device * pdev, struct pci_ecam_ops * ops)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pci_host_common_probe(struct platform_device * pdev, struct pci_ecam_ops * ops)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pci_host_common_probe(struct platform_device * pdev, struct pci_ecam_ops * ops)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pci_host_common_probe(struct platform_device * pdev, struct pci_ecam_ops * ops)
```
</details>
</li>
</ul>

# Function: <code>pci_vpd_available</code>

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
  "name": "pci_vpd_available",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585838284,
      "name": "pci_vpd_available",
      "external": false,
      "loc": "drivers/pci/vpd.c:102",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/pci/vpd.c:pci_vpd_read"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool pci_vpd_available(struct pci_dev * dev, bool check_size)
```

```json
{
  "name": "pci_vpd_available",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_vpd_available",
      "external": false,
      "loc": "drivers/pci/vpd.c:99",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029296,
      "name": "pci_vpd_available",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
    },
    {
      "addr": 18446744071594229053,
      "name": "pci_vpd_available.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
bool pci_vpd_available(struct pci_dev * dev, bool check_size)
```

```json
{
  "name": "pci_vpd_available",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588207424,
      "name": "pci_vpd_available",
      "external": false,
      "loc": "drivers/pci/vpd.c:99",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588207424,
      "name": "pci_vpd_available",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
bool pci_vpd_available(struct pci_dev * dev, bool check_size)
```

```json
{
  "name": "pci_vpd_available",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588483136,
      "name": "pci_vpd_available",
      "external": false,
      "loc": "drivers/pci/vpd.c:99",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588483136,
      "name": "pci_vpd_available",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
bool pci_vpd_available(struct pci_dev * dev, bool check_size)
```

```json
{
  "name": "pci_vpd_available",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588780896,
      "name": "pci_vpd_available",
      "external": false,
      "loc": "drivers/pci/vpd.c:99",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588780896,
      "name": "pci_vpd_available",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool pci_vpd_available(struct pci_dev * dev, bool check_size)
```
</details>
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

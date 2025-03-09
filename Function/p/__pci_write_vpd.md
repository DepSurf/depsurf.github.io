# Function: <code>__pci_write_vpd</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pci_write_vpd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587031157,
      "name": "__pci_write_vpd",
      "external": false,
      "loc": "drivers/pci/vpd.c:425",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_write"
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
  "name": "__pci_write_vpd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588209525,
      "name": "__pci_write_vpd",
      "external": false,
      "loc": "drivers/pci/vpd.c:425",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_write"
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
  "name": "__pci_write_vpd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588485205,
      "name": "__pci_write_vpd",
      "external": false,
      "loc": "drivers/pci/vpd.c:425",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_write"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t __pci_write_vpd(struct pci_dev * dev, loff_t pos, size_t count, const void * buf, bool check_size)
```

```json
{
  "name": "__pci_write_vpd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588783173,
      "name": "__pci_write_vpd",
      "external": false,
      "loc": "drivers/pci/vpd.c:455",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:pci_write_vpd_any"
      ],
      "caller_func": [
        "drivers/pci/vpd.c:vpd_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588782368,
      "name": "__pci_write_vpd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
ssize_t __pci_write_vpd(struct pci_dev * dev, loff_t pos, size_t count, const void * buf, bool check_size)
```
</details>
</li>
</ul>

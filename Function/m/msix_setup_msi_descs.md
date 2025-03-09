# Function: <code>msix_setup_msi_descs</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int msix_setup_msi_descs(struct pci_dev * dev, void * base, struct msix_entry * entries, int nvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "msix_setup_msi_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587053104,
      "name": "msix_setup_msi_descs",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:505",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:msix_capability_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587053104,
      "name": "msix_setup_msi_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
int msix_setup_msi_descs(struct pci_dev * dev, struct msix_entry * entries, int nvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "msix_setup_msi_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588240016,
      "name": "msix_setup_msi_descs",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:607",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:__pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240016,
      "name": "msix_setup_msi_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int msix_setup_msi_descs(struct pci_dev * dev, struct msix_entry * entries, int nvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "msix_setup_msi_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588515520,
      "name": "msix_setup_msi_descs",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:607",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:__pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588515520,
      "name": "msix_setup_msi_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int msix_setup_msi_descs(struct pci_dev * dev, struct msix_entry * entries, int nvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "msix_setup_msi_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588814112,
      "name": "msix_setup_msi_descs",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:609",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:__pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588814112,
      "name": "msix_setup_msi_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int msix_setup_msi_descs(struct pci_dev * dev, void * base, struct msix_entry * entries, int nvec, struct irq_affinity_desc * masks)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void * base</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, base, entries, nvec, masks</code> ➡️ <code>dev, entries, nvec, masks</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

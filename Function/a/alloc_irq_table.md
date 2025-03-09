# Function: <code>alloc_irq_table</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585561040,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3659",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585561040,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585685232,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3724",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585685232,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585912400,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3705",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585912400,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586055904,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3754",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055904,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586808448,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3170",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586808448,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586867472,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3261",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586867472,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586743120,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2627",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586743120,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2695",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298368,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071592469014,
      "name": "alloc_irq_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588605808,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2721",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588605808,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
struct irq_remap_table * alloc_irq_table(struct amd_iommu * iommu, u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590068448,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2896",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068448,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
struct irq_remap_table * alloc_irq_table(struct amd_iommu * iommu, u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590386608,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2942",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590386608,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
struct irq_remap_table * alloc_irq_table(struct amd_iommu * iommu, u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590728992,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2981",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590728992,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585816880,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3754",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585816880,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585676064,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3754",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676064,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586005920,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3754",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586005920,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```

```json
{
  "name": "alloc_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586114208,
      "name": "alloc_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3754",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:alloc_irq_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586114208,
      "name": "alloc_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev * pdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct amd_iommu * iommu</code>
</li>
<li>
<b>Param reordered. </b>
<code>devid, pdev</code> ➡️ <code>iommu, devid, pdev</code>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct irq_remap_table * alloc_irq_table(u16 devid, struct pci_dev * pdev)
```
</details>
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

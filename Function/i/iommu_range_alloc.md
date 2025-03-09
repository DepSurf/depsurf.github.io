# Function: <code>iommu_range_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268320,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:227",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268320,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267680,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:227",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267680,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579283120,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:227",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283120,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579280160,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:229",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579280160,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298864,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:229",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298864,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:230",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310848,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071579312845,
      "name": "iommu_range_alloc.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:226",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335456,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071579337511,
      "name": "iommu_range_alloc.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:214",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350672,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071579352746,
      "name": "iommu_range_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:214",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355008,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071579357082,
      "name": "iommu_range_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, long unsigned int npages, long unsigned int * handle, long unsigned int mask, unsigned int align_order)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282496256,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/powerpc/kernel/iommu.c:163",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg",
        "arch/powerpc/kernel/iommu.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282496256,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:214",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350912,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071579352986,
      "name": "iommu_range_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:214",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283120,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071579285194,
      "name": "iommu_range_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:214",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350832,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071579352906,
      "name": "iommu_range_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```

```json
{
  "name": "iommu_range_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_range_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:214",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:iommu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359280,
      "name": "iommu_range_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071579361354,
      "name": "iommu_range_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int * handle</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int mask</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int align_order</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int npages</code> ➡️ <code>long unsigned int npages</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int iommu_range_alloc(struct device * dev, struct iommu_table * tbl, unsigned int npages)
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

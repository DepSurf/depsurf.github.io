# Function: <code>iommu_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268656,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:267",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268656,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267984,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:267",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267984,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579283424,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:267",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283424,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579280432,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:269",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579280432,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299136,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:269",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299136,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:270",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311104,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071579312896,
      "name": "iommu_alloc.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:266",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335728,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071579337560,
      "name": "iommu_alloc.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:254",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350944,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071579352802,
      "name": "iommu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:254",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355280,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071579357138,
      "name": "iommu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * page, unsigned int npages, enum dma_data_direction direction, long unsigned int mask, unsigned int align_order, long unsigned int attrs)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282498144,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/powerpc/kernel/iommu.c:293",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/iommu.c:iommu_alloc_coherent",
        "arch/powerpc/kernel/iommu.c:iommu_map_page",
        "arch/powerpc/kernel/iommu.c:iommu_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282498144,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:254",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351184,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071579353042,
      "name": "iommu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:254",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283392,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071579285250,
      "name": "iommu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:254",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351104,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071579352962,
      "name": "iommu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```

```json
{
  "name": "iommu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_alloc",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:254",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359552,
      "name": "iommu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071579361410,
      "name": "iommu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
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
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * page</code>
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
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
<li>
<b>Param removed. </b>
<code>void * vaddr</code>
</li>
<li>
<b>Param type changed. </b>
<code>int direction</code> ➡️ <code>enum dma_data_direction direction</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
dma_addr_t iommu_alloc(struct device * dev, struct iommu_table * tbl, void * vaddr, unsigned int npages, int direction)
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

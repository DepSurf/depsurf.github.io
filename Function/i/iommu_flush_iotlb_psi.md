# Function: <code>iommu_flush_iotlb_psi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584310304,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1532",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:flush_unmaps",
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584310304,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584659248,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1571",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659248,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845440,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1585",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845440,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584933632,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1590",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584933632,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585355232,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1573",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585355232,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585598352,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1590",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585598352,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585723536,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1467",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585723536,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585951760,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1475",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585951760,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586094752,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1486",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094752,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586842992,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1515",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier",
        "drivers/iommu/intel/iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586842992,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586901056,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1615",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync",
        "drivers/iommu/intel/iommu.c:intel_iommu_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901056,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586780160,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1639",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier",
        "drivers/iommu/intel/iommu.c:switch_to_super_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586780160,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1643",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier",
        "drivers/iommu/intel/iommu.c:switch_to_super_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587334336,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071592473462,
      "name": "iommu_flush_iotlb_psi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1542",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier",
        "drivers/iommu/intel/iommu.c:switch_to_super_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588648464,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
    },
    {
      "addr": 18446744071594343243,
      "name": "iommu_flush_iotlb_psi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1509",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier",
        "drivers/iommu/intel/iommu.c:switch_to_super_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590121328,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071596242077,
      "name": "iommu_flush_iotlb_psi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1479",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier",
        "drivers/iommu/intel/iommu.c:switch_to_super_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590434784,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071596770496,
      "name": "iommu_flush_iotlb_psi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1419",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier",
        "drivers/iommu/intel/iommu.c:switch_to_super_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590781392,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071597679108,
      "name": "iommu_flush_iotlb_psi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585855872,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1486",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585855872,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585714896,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1486",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585714896,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586044768,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1486",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044768,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```

```json
{
  "name": "iommu_flush_iotlb_psi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152800,
      "name": "iommu_flush_iotlb_psi",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1486",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_unmap",
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152800,
      "name": "iommu_flush_iotlb_psi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu * iommu, struct dmar_domain * domain, long unsigned int pfn, unsigned int pages, int ih, int map)
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

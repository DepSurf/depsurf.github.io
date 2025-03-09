# Function: <code>swiotlb_tbl_unmap_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113664,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "lib/swiotlb.c:552",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_free_coherent",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "lib/swiotlb.c:swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113664,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407856,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "lib/swiotlb.c:552",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_map_page",
        "lib/swiotlb.c:swiotlb_free_coherent",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407856,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583533264,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "lib/swiotlb.c:592",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_map_page",
        "lib/swiotlb.c:swiotlb_free_coherent",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583533264,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570160,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "lib/swiotlb.c:592",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_unmap_page",
        "lib/swiotlb.c:swiotlb_map_page",
        "lib/swiotlb.c:swiotlb_free_coherent",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570160,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583815488,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "lib/swiotlb.c:634",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_map_page",
        "lib/swiotlb.c:swiotlb_free_coherent",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583815488,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579950816,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:618",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_free",
        "kernel/dma/swiotlb.c:swiotlb_alloc",
        "kernel/dma/swiotlb.c:swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950816,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998624,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:546",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998624,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580042224,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:573",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042224,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091248,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:580",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/intel-iommu.c:bounce_unmap_single",
        "drivers/iommu/intel-iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091248,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152144,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:581",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/intel/iommu.c:bounce_unmap_single",
        "drivers/iommu/intel/iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152144,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133424,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:596",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133424,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138384,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:556",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138384,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device * dev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580281936,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:638",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580281936,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void swiotlb_tbl_unmap_single(struct device * dev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580454320,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:670",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580454320,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void swiotlb_tbl_unmap_single(struct device * dev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700976,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:847",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700976,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swiotlb_tbl_unmap_single(struct device * dev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580778692,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:872",
      "file": "kernel/dma/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_map"
      ],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580778080,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void swiotlb_tbl_unmap_single(struct device * dev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:1434",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597411112,
      "name": "swiotlb_tbl_unmap_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580866576,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491297768,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:580",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491297768,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284224288,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:580",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "kernel/dma/swiotlb.c:swiotlb_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284224288,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271811796,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:580",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "kernel/dma/swiotlb.c:swiotlb_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271811796,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060448,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:580",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/intel-iommu.c:bounce_unmap_single",
        "drivers/iommu/intel-iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060448,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005296,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:580",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/iommu/intel-iommu.c:bounce_unmap_single",
        "drivers/iommu/intel-iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005296,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051520,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:580",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/intel-iommu.c:bounce_unmap_single",
        "drivers/iommu/intel-iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051520,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_unmap_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102272,
      "name": "swiotlb_tbl_unmap_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:580",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/intel-iommu.c:bounce_unmap_single",
        "drivers/iommu/intel-iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102272,
      "name": "swiotlb_tbl_unmap_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t mapping_size</code>
</li>
<li>
<b>Param added. </b>
<code>size_t alloc_size</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param reordered. </b>
<code>hwdev, tlb_addr, size, dir, attrs</code> ➡️ <code>hwdev, tlb_addr, mapping_size, alloc_size, dir, attrs</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t alloc_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>hwdev, tlb_addr, mapping_size, alloc_size, dir, attrs</code> ➡️ <code>hwdev, tlb_addr, mapping_size, dir, attrs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * hwdev</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void swiotlb_tbl_unmap_single(struct device * hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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

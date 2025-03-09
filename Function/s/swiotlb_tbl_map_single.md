# Function: <code>swiotlb_tbl_map_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112928,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "lib/swiotlb.c:425",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "lib/swiotlb.c:swiotlb_map_page",
        "lib/swiotlb.c:swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112928,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407184,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "lib/swiotlb.c:425",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_map_sg_attrs",
        "lib/swiotlb.c:swiotlb_map_page",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407184,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583532576,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "lib/swiotlb.c:455",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:map_single",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583532576,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570816,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "lib/swiotlb.c:455",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:map_single",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570816,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583816160,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "lib/swiotlb.c:493",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:map_single",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583816160,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:479",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_alloc",
        "kernel/dma/swiotlb.c:map_single",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953334,
      "name": "swiotlb_tbl_map_single.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579949888,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:427",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999803,
      "name": "swiotlb_tbl_map_single.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579997840,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:445",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043332,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071580041456,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:445",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/intel-iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092356,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071580090496,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:446",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/intel/iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153292,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071580151376,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:464",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591311109,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071580132576,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 838
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device * dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:505",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591253373,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071580137984,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
phys_addr_t swiotlb_tbl_map_single(struct device * dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:542",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592150531,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071580281584,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
phys_addr_t swiotlb_tbl_map_single(struct device * dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, unsigned int alloc_align_mask, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:572",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593923362,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580453952,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
phys_addr_t swiotlb_tbl_map_single(struct device * dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, unsigned int alloc_align_mask, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:742",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595993602,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071580700288,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
phys_addr_t swiotlb_tbl_map_single(struct device * dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, unsigned int alloc_align_mask, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:765",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596511849,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071580777440,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
phys_addr_t swiotlb_tbl_map_single(struct device * dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, unsigned int alloc_align_mask, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:1289",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597411058,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071580866000,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491296872,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:445",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491296872,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284222912,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:445",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "kernel/dma/swiotlb.c:swiotlb_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284222912,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1364
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271810998,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:445",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271810998,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 798
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:445",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/intel-iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061556,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071580059696,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:445",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/iommu/intel-iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006404,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071580004544,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:445",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/intel-iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052628,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071580050768,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_tbl_map_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_tbl_map_single",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:445",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/iommu/intel-iommu.c:bounce_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103396,
      "name": "swiotlb_tbl_map_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071580101520,
      "name": "swiotlb_tbl_map_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
<code>hwdev, tbl_dma_addr, orig_addr, size, dir, attrs</code> ➡️ <code>hwdev, tbl_dma_addr, orig_addr, mapping_size, alloc_size, dir, attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>dma_addr_t tbl_dma_addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>hwdev, tbl_dma_addr, orig_addr, mapping_size, alloc_size, dir, attrs</code> ➡️ <code>hwdev, orig_addr, mapping_size, alloc_size, dir, attrs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int alloc_align_mask</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, orig_addr, mapping_size, alloc_size, dir, attrs</code> ➡️ <code>dev, orig_addr, mapping_size, alloc_size, alloc_align_mask, dir, attrs</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device * hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs)
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

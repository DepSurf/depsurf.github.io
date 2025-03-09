# Function: <code>dma_free_contiguous</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580037662,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-contiguous.h:166",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580087902,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-contiguous.h:166",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580148276,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-contiguous.h:166",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586783280,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-contiguous.h:166",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580127209,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:152",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580130497,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:152",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_free_pages",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586965701,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:152",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580131529,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:152",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580134881,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:152",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_free_pages",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586846568,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:152",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580275053,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:153",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580278033,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:153",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_free_pages",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587406360,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:153",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580446618,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:153",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450017,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:153",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_free_pages",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588724066,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:153",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "dma_free_contiguous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580691050,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:164",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580695009,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:164",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_free_pages",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590209682,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:164",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "dma_free_contiguous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580767658,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:165",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580771633,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:165",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_free_pages",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590531170,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:165",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580853402,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:166",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580857697,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:166",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_free_pages",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590886642,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-map-ops.h:166",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
void dma_free_contiguous(struct device * dev, struct page * page, size_t size)
```

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491292088,
      "name": "dma_free_contiguous",
      "external": true,
      "loc": "kernel/dma/contiguous.c:264",
      "file": "kernel/dma/contiguous.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:__iommu_dma_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491292088,
      "name": "dma_free_contiguous",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void dma_free_contiguous(struct device * dev, struct page * page, size_t size)
```

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225297152,
      "name": "dma_free_contiguous",
      "external": true,
      "loc": "kernel/dma/contiguous.c:264",
      "file": "kernel/dma/contiguous.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225297152,
      "name": "dma_free_contiguous",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284216876,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-contiguous.h:166",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void dma_free_contiguous(struct device * dev, struct page * page, size_t size)
```

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271807146,
      "name": "dma_free_contiguous",
      "external": true,
      "loc": "kernel/dma/contiguous.c:264",
      "file": "kernel/dma/contiguous.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271807146,
      "name": "dma_free_contiguous",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void dma_free_contiguous(struct device * dev, struct page * page, size_t size)
```

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057424,
      "name": "dma_free_contiguous",
      "external": true,
      "loc": "kernel/dma/contiguous.c:264",
      "file": "kernel/dma/contiguous.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057424,
      "name": "dma_free_contiguous",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580001950,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-contiguous.h:166",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580048174,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-contiguous.h:166",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580098926,
      "name": "dma_free_contiguous",
      "external": false,
      "loc": "include/linux/dma-contiguous.h:166",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void dma_free_contiguous(struct device * dev, struct page * page, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void dma_free_contiguous(struct device * dev, struct page * page, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void dma_free_contiguous(struct device * dev, struct page * page, size_t size)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
void dma_free_contiguous(struct device * dev, struct page * page, size_t size)
```
</details>
</li>
</ul>

# Function: <code>init_iova_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn, long unsigned int pfn_32bit)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584272560,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:25",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584272560,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn, long unsigned int pfn_32bit)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584615328,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:36",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584615328,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn, long unsigned int pfn_32bit)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584798032,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:36",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584798032,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn, long unsigned int pfn_32bit)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584887136,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:37",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584887136,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585307296,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:42",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585307296,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585548208,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:42",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585548208,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585672624,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:42",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672624,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585901057,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:30",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902877,
      "name": "init_iova_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585901040,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586043968,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:30",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043968,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586790976,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:30",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_setup_dma_ops",
        "drivers/iommu/intel/iommu.c:dmar_init_reserved_ranges"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790976,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974608,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:31",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974608,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586855600,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:48",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855600,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:48",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592485053,
      "name": "init_iova_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587417344,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:47",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594354022,
      "name": "init_iova_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588730432,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:52",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596245216,
      "name": "init_iova_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071590215392,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:52",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596773583,
      "name": "init_iova_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071590534688,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:53",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597682859,
      "name": "init_iova_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071590890576,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498859856,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:30",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_setup_dma_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498859856,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585804944,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:30",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804944,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585664128,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:30",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664128,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585993984,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:30",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585993984,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```

```json
{
  "name": "init_iova_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586101008,
      "name": "init_iova_domain",
      "external": true,
      "loc": "drivers/iommu/iova.c:30",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586101008,
      "name": "init_iova_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int pfn_32bit</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void init_iova_domain(struct iova_domain * iovad, long unsigned int granule, long unsigned int start_pfn)
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

# Function: <code>free_iova_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584614464,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:443",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:__queue_flush",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614464,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584798352,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:443",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:__queue_flush",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584798352,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584887472,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:417",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584887472,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585307696,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:442",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585307696,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585548608,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:442",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585548608,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585673008,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:451",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673008,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585900336,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:450",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585900336,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043248,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:450",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:bounce_map_single",
        "drivers/iommu/intel-iommu.c:intel_unmap",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043248,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586792333,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:450",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:fq_ring_free"
      ],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova",
        "drivers/iommu/intel/iommu.c:bounce_map_single",
        "drivers/iommu/intel/iommu.c:intel_map_sg",
        "drivers/iommu/intel/iommu.c:intel_unmap",
        "drivers/iommu/intel/iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793056,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586975088,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:465",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova",
        "drivers/iommu/iova.c:fq_ring_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975088,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586856912,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:531",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova",
        "drivers/iommu/iova.c:fq_ring_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586856912,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587418448,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:532",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova",
        "drivers/iommu/iova.c:fq_ring_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587418448,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588734704,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:482",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova",
        "drivers/iommu/dma-iommu.c:fq_ring_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588734704,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590219872,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:487",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova",
        "drivers/iommu/dma-iommu.c:fq_ring_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590219872,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590539552,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:487",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova",
        "drivers/iommu/dma-iommu.c:fq_ring_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590539552,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 691
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590893360,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:488",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova",
        "drivers/iommu/dma-iommu.c:fq_ring_free_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590893360,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498862312,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:450",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498862312,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585804224,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:450",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:bounce_map_single",
        "drivers/iommu/intel-iommu.c:intel_unmap",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804224,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585663408,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:450",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:bounce_map_single",
        "drivers/iommu/intel-iommu.c:intel_unmap",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663408,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585993264,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:450",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:bounce_map_single",
        "drivers/iommu/intel-iommu.c:intel_unmap",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585993264,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "free_iova_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586102080,
      "name": "free_iova_fast",
      "external": true,
      "loc": "drivers/iommu/iova.c:450",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:bounce_map_single",
        "drivers/iommu/intel-iommu.c:intel_unmap",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586102080,
      "name": "free_iova_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void free_iova_fast(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
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

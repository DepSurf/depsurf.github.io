# Function: <code>iommu_unmap_fast</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585293792,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1627",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585293792,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585534480,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1633",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585534480,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585659600,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1709",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659600,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585885888,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1930",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585885888,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028160,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1987",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028160,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586769424,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2314",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap",
        "drivers/vfio/vfio_iommu_type1.c:unmap_unpin_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769424,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950208,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2534",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap",
        "drivers/vfio/vfio_iommu_type1.c:unmap_unpin_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950208,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586829648,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2565",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586829648,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587390112,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2651",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587390112,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701568,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2428",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701568,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182736,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2492",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182736,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590507008,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2504",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590507008,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590860352,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2768",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590860352,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498829664,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1987",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498829664,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231434528,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1987",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231434528,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292040432,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1987",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292040432,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585789136,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1987",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585789136,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585648320,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1987",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585648320,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585978176,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1987",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978176,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "iommu_unmap_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586086000,
      "name": "iommu_unmap_fast",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1987",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586086000,
      "name": "iommu_unmap_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size)
```
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_iotlb_gather * iotlb_gather</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
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

# Function: <code>__iommu_dma_unmap</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "__iommu_dma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586781616,
      "name": "__iommu_dma_unmap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:456",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586781616,
      "name": "__iommu_dma_unmap",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "__iommu_dma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586962336,
      "name": "__iommu_dma_unmap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:488",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586962336,
      "name": "__iommu_dma_unmap",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "__iommu_dma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586844128,
      "name": "__iommu_dma_unmap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:474",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844128,
      "name": "__iommu_dma_unmap",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "__iommu_dma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_dma_unmap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:490",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408176,
      "name": "__iommu_dma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071592484427,
      "name": "__iommu_dma_unmap.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "__iommu_dma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_dma_unmap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:663",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_free",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588720720,
      "name": "__iommu_dma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071594353393,
      "name": "__iommu_dma_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "__iommu_dma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_dma_unmap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:674",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_free",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590204736,
      "name": "__iommu_dma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071596244931,
      "name": "__iommu_dma_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "__iommu_dma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_dma_unmap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:707",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_free",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590526192,
      "name": "__iommu_dma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071596773331,
      "name": "__iommu_dma_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "__iommu_dma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_dma_unmap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:826",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_free",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590881456,
      "name": "__iommu_dma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071597682559,
      "name": "__iommu_dma_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "__iommu_dma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498843000,
      "name": "__iommu_dma_unmap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:441",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498843000,
      "name": "__iommu_dma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void __iommu_dma_unmap(struct device * dev, dma_addr_t dma_addr, size_t size)
```
</details>
</li>
</ul>

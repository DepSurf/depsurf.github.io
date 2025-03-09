# Function: <code>iommu_dma_free_iova</code>

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
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size)
```

```json
{
  "name": "iommu_dma_free_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586781536,
      "name": "iommu_dma_free_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:440",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586781536,
      "name": "iommu_dma_free_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size, struct page * freelist)
```

```json
{
  "name": "iommu_dma_free_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586962256,
      "name": "iommu_dma_free_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:471",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586962256,
      "name": "iommu_dma_free_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size, struct page * freelist)
```

```json
{
  "name": "iommu_dma_free_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586844048,
      "name": "iommu_dma_free_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:457",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844048,
      "name": "iommu_dma_free_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size, struct iommu_iotlb_gather * gather)
```

```json
{
  "name": "iommu_dma_free_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_free_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:473",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407936,
      "name": "iommu_dma_free_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071592484266,
      "name": "iommu_dma_free_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size, struct iommu_iotlb_gather * gather)
```

```json
{
  "name": "iommu_dma_free_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_free_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:646",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588719952,
      "name": "iommu_dma_free_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071594353240,
      "name": "iommu_dma_free_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size, struct iommu_iotlb_gather * gather)
```

```json
{
  "name": "iommu_dma_free_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_free_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:657",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590203952,
      "name": "iommu_dma_free_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071596244778,
      "name": "iommu_dma_free_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size, struct iommu_iotlb_gather * gather)
```

```json
{
  "name": "iommu_dma_free_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_free_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:690",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590525408,
      "name": "iommu_dma_free_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071596773178,
      "name": "iommu_dma_free_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size, struct iommu_iotlb_gather * gather)
```

```json
{
  "name": "iommu_dma_free_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_free_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:809",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590881168,
      "name": "iommu_dma_free_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071597682398,
      "name": "iommu_dma_free_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size)
```

```json
{
  "name": "iommu_dma_free_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498842848,
      "name": "iommu_dma_free_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:425",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498842848,
      "name": "iommu_dma_free_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page * freelist</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_iotlb_gather * gather</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * freelist</code>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void iommu_dma_free_iova(struct iommu_dma_cookie * cookie, dma_addr_t iova, size_t size)
```
</details>
</li>
</ul>

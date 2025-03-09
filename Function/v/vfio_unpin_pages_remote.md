# Function: <code>vfio_unpin_pages_remote</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587051920,
      "name": "vfio_unpin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:476",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051920,
      "name": "vfio_unpin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587882768,
      "name": "vfio_unpin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:566",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587882768,
      "name": "vfio_unpin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587944528,
      "name": "vfio_unpin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:589",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587944528,
      "name": "vfio_unpin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587825824,
      "name": "vfio_unpin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:760",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825824,
      "name": "vfio_unpin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588430720,
      "name": "vfio_unpin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:761",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588430720,
      "name": "vfio_unpin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589829728,
      "name": "vfio_unpin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:759",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589829728,
      "name": "vfio_unpin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586699840,
      "name": "vfio_unpin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:476",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699840,
      "name": "vfio_unpin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587006480,
      "name": "vfio_unpin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:476",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587006480,
      "name": "vfio_unpin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587113648,
      "name": "vfio_unpin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:476",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113648,
      "name": "vfio_unpin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
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
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma * dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting)
```
</details>
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

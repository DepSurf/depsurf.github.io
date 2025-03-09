# Function: <code>update_user_bitmap</code>

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
int update_user_bitmap(u64 * bitmap, struct vfio_iommu * iommu, struct vfio_dma * dma, dma_addr_t base_iova, size_t pgsize)
```

```json
{
  "name": "update_user_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587886448,
      "name": "update_user_bitmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:978",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587886448,
      "name": "update_user_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int update_user_bitmap(u64 * bitmap, struct vfio_iommu * iommu, struct vfio_dma * dma, dma_addr_t base_iova, size_t pgsize)
```

```json
{
  "name": "update_user_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587948000,
      "name": "update_user_bitmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1003",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587948000,
      "name": "update_user_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int update_user_bitmap(u64 * bitmap, struct vfio_iommu * iommu, struct vfio_dma * dma, dma_addr_t base_iova, size_t pgsize)
```

```json
{
  "name": "update_user_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587834096,
      "name": "update_user_bitmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1201",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587834096,
      "name": "update_user_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
int update_user_bitmap(u64 * bitmap, struct vfio_iommu * iommu, struct vfio_dma * dma, dma_addr_t base_iova, size_t pgsize)
```

```json
{
  "name": "update_user_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_user_bitmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1202",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427616,
      "name": "update_user_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    },
    {
      "addr": 18446744071592548413,
      "name": "update_user_bitmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int update_user_bitmap(u64 * bitmap, struct vfio_iommu * iommu, struct vfio_dma * dma, dma_addr_t base_iova, size_t pgsize)
```

```json
{
  "name": "update_user_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_user_bitmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1200",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589826848,
      "name": "update_user_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071594427579,
      "name": "update_user_bitmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int update_user_bitmap(u64 * bitmap, struct vfio_iommu * iommu, struct vfio_dma * dma, dma_addr_t base_iova, size_t pgsize)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int update_user_bitmap(u64 * bitmap, struct vfio_iommu * iommu, struct vfio_dma * dma, dma_addr_t base_iova, size_t pgsize)
```
</details>
</li>
</ul>

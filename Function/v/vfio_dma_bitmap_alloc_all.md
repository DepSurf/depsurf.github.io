# Function: <code>vfio_dma_bitmap_alloc_all</code>

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
int vfio_dma_bitmap_alloc_all(struct vfio_iommu * iommu, size_t pgsize)
```

```json
{
  "name": "vfio_dma_bitmap_alloc_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587882464,
      "name": "vfio_dma_bitmap_alloc_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:239",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587882464,
      "name": "vfio_dma_bitmap_alloc_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int vfio_dma_bitmap_alloc_all(struct vfio_iommu * iommu, size_t pgsize)
```

```json
{
  "name": "vfio_dma_bitmap_alloc_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587943968,
      "name": "vfio_dma_bitmap_alloc_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:252",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587943968,
      "name": "vfio_dma_bitmap_alloc_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_dma_bitmap_alloc_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587835364,
      "name": "vfio_dma_bitmap_alloc_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:290",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_dma_bitmap_alloc_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588436070,
      "name": "vfio_dma_bitmap_alloc_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:291",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_dma_bitmap_alloc_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589847553,
      "name": "vfio_dma_bitmap_alloc_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:289",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages"
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
int vfio_dma_bitmap_alloc_all(struct vfio_iommu * iommu, size_t pgsize)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int vfio_dma_bitmap_alloc_all(struct vfio_iommu * iommu, size_t pgsize)
```
</details>
</li>
</ul>

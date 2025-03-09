# Function: <code>unmap_unpin_fast</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmap_unpin_fast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587052657,
      "name": "unmap_unpin_fast",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:694",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
size_t unmap_unpin_fast(struct vfio_domain * domain, struct vfio_dma * dma, dma_addr_t * iova, size_t len, phys_addr_t phys, long int * unlocked, struct list_head * unmapped_list, int * unmapped_cnt, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "unmap_unpin_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587883280,
      "name": "unmap_unpin_fast",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:803",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587883280,
      "name": "unmap_unpin_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
size_t unmap_unpin_fast(struct vfio_domain * domain, struct vfio_dma * dma, dma_addr_t * iova, size_t len, phys_addr_t phys, long int * unlocked, struct list_head * unmapped_list, int * unmapped_cnt, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "unmap_unpin_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587945040,
      "name": "unmap_unpin_fast",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:827",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587945040,
      "name": "unmap_unpin_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
  "name": "unmap_unpin_fast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587826671,
      "name": "unmap_unpin_fast",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1021",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
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
  "name": "unmap_unpin_fast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588431588,
      "name": "unmap_unpin_fast",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1022",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
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
  "name": "unmap_unpin_fast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589830680,
      "name": "unmap_unpin_fast",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1020",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmap_unpin_fast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586700577,
      "name": "unmap_unpin_fast",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:694",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
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
  "name": "unmap_unpin_fast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587007217,
      "name": "unmap_unpin_fast",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:694",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
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
  "name": "unmap_unpin_fast",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587114380,
      "name": "unmap_unpin_fast",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:694",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
size_t unmap_unpin_fast(struct vfio_domain * domain, struct vfio_dma * dma, dma_addr_t * iova, size_t len, phys_addr_t phys, long int * unlocked, struct list_head * unmapped_list, int * unmapped_cnt, struct iommu_iotlb_gather * iotlb_gather)
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
size_t unmap_unpin_fast(struct vfio_domain * domain, struct vfio_dma * dma, dma_addr_t * iova, size_t len, phys_addr_t phys, long int * unlocked, struct list_head * unmapped_list, int * unmapped_cnt, struct iommu_iotlb_gather * iotlb_gather)
```
</details>
</li>
</ul>

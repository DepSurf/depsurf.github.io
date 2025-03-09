# Function: <code>vfio_iommu_type1_dma_rw_chunk</code>

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
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu * iommu, dma_addr_t user_iova, void * data, size_t count, bool write, size_t * copied)
```

```json
{
  "name": "vfio_iommu_type1_dma_rw_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587889584,
      "name": "vfio_iommu_type1_dma_rw_chunk",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2854",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587889584,
      "name": "vfio_iommu_type1_dma_rw_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu * iommu, dma_addr_t user_iova, void * data, size_t count, bool write, size_t * copied)
```

```json
{
  "name": "vfio_iommu_type1_dma_rw_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587949456,
      "name": "vfio_iommu_type1_dma_rw_chunk",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2910",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587949456,
      "name": "vfio_iommu_type1_dma_rw_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
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
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu * iommu, dma_addr_t user_iova, void * data, size_t count, bool write, size_t * copied)
```

```json
{
  "name": "vfio_iommu_type1_dma_rw_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587828384,
      "name": "vfio_iommu_type1_dma_rw_chunk",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:3135",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587828384,
      "name": "vfio_iommu_type1_dma_rw_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu * iommu, dma_addr_t user_iova, void * data, size_t count, bool write, size_t * copied)
```

```json
{
  "name": "vfio_iommu_type1_dma_rw_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_type1_dma_rw_chunk",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:3137",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433264,
      "name": "vfio_iommu_type1_dma_rw_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071592548702,
      "name": "vfio_iommu_type1_dma_rw_chunk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu * iommu, dma_addr_t user_iova, void * data, size_t count, bool write, size_t * copied)
```

```json
{
  "name": "vfio_iommu_type1_dma_rw_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_type1_dma_rw_chunk",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:3129",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589833088,
      "name": "vfio_iommu_type1_dma_rw_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
    },
    {
      "addr": 18446744071594427868,
      "name": "vfio_iommu_type1_dma_rw_chunk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu * iommu, dma_addr_t user_iova, void * data, size_t count, bool write, size_t * copied)
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
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu * iommu, dma_addr_t user_iova, void * data, size_t count, bool write, size_t * copied)
```
</details>
</li>
</ul>

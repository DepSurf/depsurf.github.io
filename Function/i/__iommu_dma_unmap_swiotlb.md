# Function: <code>__iommu_dma_unmap_swiotlb</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __iommu_dma_unmap_swiotlb(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "__iommu_dma_unmap_swiotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586963200,
      "name": "__iommu_dma_unmap_swiotlb",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:510",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg_swiotlb",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963200,
      "name": "__iommu_dma_unmap_swiotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void __iommu_dma_unmap_swiotlb(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "__iommu_dma_unmap_swiotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586844928,
      "name": "__iommu_dma_unmap_swiotlb",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:496",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844928,
      "name": "__iommu_dma_unmap_swiotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void __iommu_dma_unmap_swiotlb(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "__iommu_dma_unmap_swiotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587408512,
      "name": "__iommu_dma_unmap_swiotlb",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:513",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408512,
      "name": "__iommu_dma_unmap_swiotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __iommu_dma_unmap_swiotlb(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __iommu_dma_unmap_swiotlb(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
</ul>

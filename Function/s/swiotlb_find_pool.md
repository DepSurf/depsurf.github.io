# Function: <code>swiotlb_find_pool</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_tlb_pool * swiotlb_find_pool(struct device * dev, phys_addr_t paddr)
```

```json
{
  "name": "swiotlb_find_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864640,
      "name": "swiotlb_find_pool",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:771",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_single_for_device",
        "kernel/dma/mapping.c:dma_sync_single_for_cpu",
        "kernel/dma/mapping.c:dma_unmap_page_attrs",
        "kernel/dma/mapping.c:dma_unmap_page_attrs",
        "kernel/dma/direct.c:dma_direct_need_sync",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_release_slots",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864640,
      "name": "swiotlb_find_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct io_tlb_pool * swiotlb_find_pool(struct device * dev, phys_addr_t paddr)
```
</details>
</li>
</ul>

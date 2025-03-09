# Struct: <code>iommu_domain_ops</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain_ops {
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    bool (*)(struct iommu_domain *) enforce_cache_coherency;
    int (*)(struct iommu_domain *) enable_nesting;
    int (*)(struct iommu_domain *, long unsigned int) set_pgtable_quirks;
    void (*)(struct iommu_domain *) free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain_ops {
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, struct device *, ioasid_t) set_dev_pasid;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    bool (*)(struct iommu_domain *) enforce_cache_coherency;
    int (*)(struct iommu_domain *) enable_nesting;
    int (*)(struct iommu_domain *, long unsigned int) set_pgtable_quirks;
    void (*)(struct iommu_domain *) free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain_ops {
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    int (*)(struct iommu_domain *, struct device *, ioasid_t) set_dev_pasid;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    bool (*)(struct iommu_domain *) enforce_cache_coherency;
    int (*)(struct iommu_domain *) enable_nesting;
    int (*)(struct iommu_domain *, long unsigned int) set_pgtable_quirks;
    void (*)(struct iommu_domain *) free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain_ops {
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    int (*)(struct iommu_domain *, struct device *, ioasid_t) set_dev_pasid;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    int (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    int (*)(struct iommu_domain *, struct iommu_user_data_array *) cache_invalidate_user;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    bool (*)(struct iommu_domain *) enforce_cache_coherency;
    int (*)(struct iommu_domain *) enable_nesting;
    int (*)(struct iommu_domain *, long unsigned int) set_pgtable_quirks;
    void (*)(struct iommu_domain *) free;
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct iommu_domain_ops {
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    bool (*)(struct iommu_domain *) enforce_cache_coherency;
    int (*)(struct iommu_domain *) enable_nesting;
    int (*)(struct iommu_domain *, long unsigned int) set_pgtable_quirks;
    void (*)(struct iommu_domain *) free;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct iommu_domain *, struct device *, ioasid_t) set_dev_pasid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, struct device *) detach_dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct iommu_domain *, struct iommu_user_data_array *) cache_invalidate_user</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_sync_map</code> ➡️ <code>int (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_sync_map</code>
</li>
</ul>
</details>
</li>
</ul>

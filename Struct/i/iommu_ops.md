# Struct: <code>iommu_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t) unmap;
    size_t (*)(struct iommu_domain *, long unsigned int, struct scatterlist *, unsigned int, int) map_sg;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_dm_regions;
    void (*)(struct device *, struct list_head *) put_dm_regions;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct iommu_domain *, u32) domain_set_windows;
    u32 (*)(struct iommu_domain *) domain_get_windows;
    long unsigned int pgsize_bitmap;
    void * priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t) unmap;
    size_t (*)(struct iommu_domain *, long unsigned int, struct scatterlist *, unsigned int, int) map_sg;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_dm_regions;
    void (*)(struct device *, struct list_head *) put_dm_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_dm_region *) apply_dm_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct iommu_domain *, u32) domain_set_windows;
    u32 (*)(struct iommu_domain *) domain_get_windows;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t) unmap;
    size_t (*)(struct iommu_domain *, long unsigned int, struct scatterlist *, unsigned int, int) map_sg;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct iommu_domain *, u32) domain_set_windows;
    u32 (*)(struct iommu_domain *) domain_get_windows;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t) unmap;
    size_t (*)(struct iommu_domain *, long unsigned int, struct scatterlist *, unsigned int, int) map_sg;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct iommu_domain *, u32) domain_set_windows;
    u32 (*)(struct iommu_domain *) domain_get_windows;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t) unmap;
    size_t (*)(struct iommu_domain *, long unsigned int, struct scatterlist *, unsigned int, int) map_sg;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_range_add;
    void (*)(struct iommu_domain *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct iommu_domain *, u32) domain_set_windows;
    u32 (*)(struct iommu_domain *) domain_get_windows;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t) unmap;
    size_t (*)(struct iommu_domain *, long unsigned int, struct scatterlist *, unsigned int, int) map_sg;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_range_add;
    void (*)(struct iommu_domain *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct iommu_domain *, u32) domain_set_windows;
    u32 (*)(struct iommu_domain *) domain_get_windows;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_range_add;
    void (*)(struct iommu_domain *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_range_add;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    int (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    int (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    struct iommu_device * (*)(struct device *) probe_device;
    void (*)(struct device *) release_device;
    void (*)(struct device *) probe_finalize;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    int (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    int (*)(struct iommu_domain *, struct device *, struct iommu_cache_invalidate_info *) cache_invalidate;
    int (*)(struct iommu_domain *, struct device *, struct iommu_gpasid_bind_data *) sva_bind_gpasid;
    int (*)(struct device *, int) sva_unbind_gpasid;
    int (*)(struct device *) def_domain_type;
    long unsigned int pgsize_bitmap;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    struct iommu_device * (*)(struct device *) probe_device;
    void (*)(struct device *) release_device;
    void (*)(struct device *) probe_finalize;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    u32 (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    int (*)(struct iommu_domain *, struct device *, struct iommu_cache_invalidate_info *) cache_invalidate;
    int (*)(struct iommu_domain *, struct device *, struct iommu_gpasid_bind_data *) sva_bind_gpasid;
    int (*)(struct device *, u32) sva_unbind_gpasid;
    int (*)(struct device *) def_domain_type;
    long unsigned int pgsize_bitmap;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    struct iommu_device * (*)(struct device *) probe_device;
    void (*)(struct device *) release_device;
    void (*)(struct device *) probe_finalize;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *) enable_nesting;
    int (*)(struct iommu_domain *, long unsigned int) set_pgtable_quirks;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    u32 (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    int (*)(struct iommu_domain *, struct device *, struct iommu_cache_invalidate_info *) cache_invalidate;
    int (*)(struct iommu_domain *, struct device *, struct iommu_gpasid_bind_data *) sva_bind_gpasid;
    int (*)(struct device *, u32) sva_unbind_gpasid;
    int (*)(struct device *) def_domain_type;
    long unsigned int pgsize_bitmap;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
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
    struct iommu_device * (*)(struct device *) probe_device;
    void (*)(struct device *) release_device;
    void (*)(struct device *) probe_finalize;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *) enable_nesting;
    int (*)(struct iommu_domain *, long unsigned int) set_pgtable_quirks;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    u32 (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    int (*)(struct iommu_domain *, struct device *, struct iommu_cache_invalidate_info *) cache_invalidate;
    int (*)(struct iommu_domain *, struct device *, struct iommu_gpasid_bind_data *) sva_bind_gpasid;
    int (*)(struct device *, u32) sva_unbind_gpasid;
    int (*)(struct device *) def_domain_type;
    long unsigned int pgsize_bitmap;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    struct iommu_device * (*)(struct device *) probe_device;
    void (*)(struct device *) release_device;
    void (*)(struct device *) probe_finalize;
    struct iommu_group * (*)(struct device *) device_group;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    u32 (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    int (*)(struct device *) def_domain_type;
    const struct iommu_domain_ops * default_domain_ops;
    long unsigned int pgsize_bitmap;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(struct device *, enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    struct iommu_device * (*)(struct device *) probe_device;
    void (*)(struct device *) release_device;
    void (*)(struct device *) probe_finalize;
    struct iommu_group * (*)(struct device *) device_group;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct device *) is_attach_deferred;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    int (*)(struct device *) def_domain_type;
    void (*)(struct device *, ioasid_t) remove_dev_pasid;
    const struct iommu_domain_ops * default_domain_ops;
    long unsigned int pgsize_bitmap;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(struct device *, enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    struct iommu_device * (*)(struct device *) probe_device;
    void (*)(struct device *) release_device;
    void (*)(struct device *) probe_finalize;
    void (*)(struct device *) set_platform_dma_ops;
    struct iommu_group * (*)(struct device *) device_group;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct device *) is_attach_deferred;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    int (*)(struct device *) def_domain_type;
    void (*)(struct device *, ioasid_t) remove_dev_pasid;
    const struct iommu_domain_ops * default_domain_ops;
    long unsigned int pgsize_bitmap;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(struct device *, enum iommu_cap) capable;
    void * (*)(struct device *, u32 *, u32 *) hw_info;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    struct iommu_domain * (*)(struct device *, u32, struct iommu_domain *, const struct iommu_user_data *) domain_alloc_user;
    struct iommu_domain * (*)(struct device *) domain_alloc_paging;
    struct iommu_device * (*)(struct device *) probe_device;
    void (*)(struct device *) release_device;
    void (*)(struct device *) probe_finalize;
    struct iommu_group * (*)(struct device *) device_group;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct device *) is_attach_deferred;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    int (*)(struct device *) def_domain_type;
    void (*)(struct device *, ioasid_t) remove_dev_pasid;
    const struct iommu_domain_ops * default_domain_ops;
    long unsigned int pgsize_bitmap;
    struct module * owner;
    struct iommu_domain * identity_domain;
    struct iommu_domain * blocked_domain;
    struct iommu_domain * default_domain;
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
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    int (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    int (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    int (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct iommu_ops {
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    int (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    int (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    int (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    long unsigned int pgsize_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct iommu_ops {
    bool (*)(enum iommu_cap) capable;
    struct iommu_domain * (*)(unsigned int) domain_alloc;
    void (*)(struct iommu_domain *) domain_free;
    int (*)(struct iommu_domain *, struct device *) attach_dev;
    void (*)(struct iommu_domain *, struct device *) detach_dev;
    int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    void (*)(struct iommu_domain *) flush_iotlb_all;
    void (*)(struct iommu_domain *) iotlb_sync_map;
    void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync;
    phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys;
    int (*)(struct device *) add_device;
    void (*)(struct device *) remove_device;
    struct iommu_group * (*)(struct device *) device_group;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr;
    int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr;
    void (*)(struct device *, struct list_head *) get_resv_regions;
    void (*)(struct device *, struct list_head *) put_resv_regions;
    void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region;
    int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable;
    void (*)(struct iommu_domain *, u32) domain_window_disable;
    int (*)(struct device *, struct of_phandle_args *) of_xlate;
    bool (*)(struct iommu_domain *, struct device *) is_attach_deferred;
    bool (*)(struct device *, enum iommu_dev_features) dev_has_feat;
    bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled;
    int (*)(struct device *, enum iommu_dev_features) dev_enable_feat;
    int (*)(struct device *, enum iommu_dev_features) dev_disable_feat;
    int (*)(struct iommu_domain *, struct device *) aux_attach_dev;
    void (*)(struct iommu_domain *, struct device *) aux_detach_dev;
    int (*)(struct iommu_domain *, struct device *) aux_get_pasid;
    struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind;
    void (*)(struct iommu_sva *) sva_unbind;
    int (*)(struct iommu_sva *) sva_get_pasid;
    int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response;
    long unsigned int pgsize_bitmap;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, struct iommu_domain *, struct iommu_dm_region *) apply_dm_region</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct device *, struct of_phandle_args *) of_xlate</code>
</li>
<li>
<b>Field removed. </b>
<code>void * priv</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, struct list_head *) get_resv_regions</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, struct list_head *) put_resv_regions</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *, struct list_head *) get_dm_regions</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *, struct list_head *) put_dm_regions</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *, struct iommu_domain *, struct iommu_dm_region *) apply_dm_region</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct iommu_domain *) flush_iotlb_all</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_range_add</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct iommu_domain *) iotlb_sync</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct iommu_domain *, struct device *) is_attach_deferred</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>size_t (*)(struct iommu_domain *, long unsigned int, struct scatterlist *, unsigned int, int) map_sg</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, u32) domain_set_windows</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 (*)(struct iommu_domain *) domain_get_windows</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct iommu_domain *) iotlb_sync_map</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct device *, enum iommu_dev_features) dev_has_feat</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct device *, enum iommu_dev_features) dev_enable_feat</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct device *, enum iommu_dev_features) dev_disable_feat</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iommu_domain *, struct device *) aux_attach_dev</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct iommu_domain *, struct device *) aux_detach_dev</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iommu_domain *, struct device *) aux_get_pasid</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct iommu_sva *) sva_unbind</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iommu_sva *) sva_get_pasid</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_range_add</code>
</li>
<li>
<b>Field type changed. </b>
<code>size_t (*)(struct iommu_domain *, long unsigned int, size_t) unmap</code> ➡️ <code>size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct iommu_domain *) iotlb_sync</code> ➡️ <code>void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct iommu_device * (*)(struct device *) probe_device</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct device *) release_device</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct device *) probe_finalize</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iommu_domain *, struct device *, struct iommu_cache_invalidate_info *) cache_invalidate</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iommu_domain *, struct device *, struct iommu_gpasid_bind_data *) sva_bind_gpasid</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct device *, int) sva_unbind_gpasid</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct device *) def_domain_type</code>
</li>
<li>
<b>Field added. </b>
<code>struct module * owner</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *) add_device</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *) remove_device</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map</code> ➡️ <code>int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct iommu_sva *) sva_get_pasid</code> ➡️ <code>u32 (*)(struct iommu_sva *) sva_get_pasid</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct device *, int) sva_unbind_gpasid</code> ➡️ <code>int (*)(struct device *, u32) sva_unbind_gpasid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct iommu_domain *) enable_nesting</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iommu_domain *, long unsigned int) set_pgtable_quirks</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, u32) domain_window_disable</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct iommu_domain *) iotlb_sync_map</code> ➡️ <code>void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_sync_map</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages</code>
</li>
<li>
<b>Field added. </b>
<code>size_t (*)(struct iommu_domain *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct iommu_domain_ops * default_domain_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *) domain_free</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, struct device *) attach_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, struct device *) detach_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t (*)(struct iommu_domain *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *) flush_iotlb_all</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, long unsigned int, size_t) iotlb_sync_map</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync</code>
</li>
<li>
<b>Field removed. </b>
<code>phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *) enable_nesting</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, long unsigned int) set_pgtable_quirks</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, struct device *) aux_attach_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, struct device *) aux_detach_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, struct device *) aux_get_pasid</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, struct device *, struct iommu_cache_invalidate_info *) cache_invalidate</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, struct device *, struct iommu_gpasid_bind_data *) sva_bind_gpasid</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, u32) sva_unbind_gpasid</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct iommu_domain *, struct device *) is_attach_deferred</code> ➡️ <code>bool (*)(struct device *) is_attach_deferred</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, ioasid_t) remove_dev_pasid</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *, struct list_head *) put_resv_regions</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct device *, enum iommu_dev_features) dev_has_feat</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_sva *) sva_unbind</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 (*)(struct iommu_sva *) sva_get_pasid</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(enum iommu_cap) capable</code> ➡️ <code>bool (*)(struct device *, enum iommu_cap) capable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct device *) set_platform_dma_ops</code>
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
<code>void * (*)(struct device *, u32 *, u32 *) hw_info</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_domain * (*)(struct device *, u32, struct iommu_domain *, const struct iommu_user_data *) domain_alloc_user</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_domain * (*)(struct device *) domain_alloc_paging</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_domain * identity_domain</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_domain * blocked_domain</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_domain * default_domain</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *) set_platform_dma_ops</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool (*)(enum iommu_cap) capable</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iommu_domain * (*)(unsigned int) domain_alloc</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *) domain_free</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, struct device *) attach_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, struct device *) detach_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, long unsigned int, phys_addr_t, size_t, int) map</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t (*)(struct iommu_domain *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *) flush_iotlb_all</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *) iotlb_sync_map</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, struct iommu_iotlb_gather *) iotlb_sync</code>
</li>
<li>
<b>Field removed. </b>
<code>phys_addr_t (*)(struct iommu_domain *, dma_addr_t) iova_to_phys</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *) add_device</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *) remove_device</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iommu_group * (*)(struct device *) device_group</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_get_attr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, enum iommu_attr, void *) domain_set_attr</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *, struct list_head *) get_resv_regions</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *, struct list_head *) put_resv_regions</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *, struct iommu_domain *, struct iommu_resv_region *) apply_resv_region</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, u32, phys_addr_t, u64, int) domain_window_enable</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, u32) domain_window_disable</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, struct of_phandle_args *) of_xlate</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct iommu_domain *, struct device *) is_attach_deferred</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct device *, enum iommu_dev_features) dev_has_feat</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct device *, enum iommu_dev_features) dev_feat_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, enum iommu_dev_features) dev_enable_feat</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, enum iommu_dev_features) dev_disable_feat</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, struct device *) aux_attach_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_domain *, struct device *) aux_detach_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_domain *, struct device *) aux_get_pasid</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iommu_sva * (*)(struct device *, struct mm_struct *, void *) sva_bind</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct iommu_sva *) sva_unbind</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct iommu_sva *) sva_get_pasid</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, struct iommu_fault_event *, struct iommu_page_response *) page_response</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int pgsize_bitmap</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
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

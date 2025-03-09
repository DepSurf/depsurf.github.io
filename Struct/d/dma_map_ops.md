# Struct: <code>dma_map_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, struct dma_attrs *) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, struct dma_attrs *) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, struct dma_attrs *) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, struct dma_attrs *) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, struct dma_attrs *) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, struct dma_attrs *) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, struct dma_attrs *) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, struct dma_attrs *) unmap_sg;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    int (*)(struct device *, dma_addr_t) mapping_error;
    int (*)(struct device *, u64) dma_supported;
    int (*)(struct device *, u64) set_dma_mask;
    int is_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    int (*)(struct device *, dma_addr_t) mapping_error;
    int (*)(struct device *, u64) dma_supported;
    int (*)(struct device *, u64) set_dma_mask;
    int is_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    int (*)(struct device *, dma_addr_t) mapping_error;
    int (*)(struct device *, u64) dma_supported;
    int (*)(struct device *, u64) set_dma_mask;
    int is_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    int (*)(struct device *, dma_addr_t) mapping_error;
    int (*)(struct device *, u64) dma_supported;
    int is_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, dma_addr_t) mapping_error;
    int (*)(struct device *, u64) dma_supported;
    int is_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, dma_addr_t) mapping_error;
    int (*)(struct device *, u64) dma_supported;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    struct page * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_pages;
    void (*)(struct device *, size_t, struct page *, dma_addr_t, enum dma_data_direction) free_pages;
    void * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_noncoherent;
    void (*)(struct device *, size_t, void *, dma_addr_t, enum dma_data_direction) free_noncoherent;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    struct page * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_pages;
    void (*)(struct device *, size_t, struct page *, dma_addr_t, enum dma_data_direction) free_pages;
    struct sg_table * (*)(struct device *, size_t, enum dma_data_direction, gfp_t, long unsigned int) alloc_noncontiguous;
    void (*)(struct device *, size_t, struct sg_table *, enum dma_data_direction) free_noncontiguous;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    struct page * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_pages;
    void (*)(struct device *, size_t, struct page *, dma_addr_t, enum dma_data_direction) free_pages;
    struct sg_table * (*)(struct device *, size_t, enum dma_data_direction, gfp_t, long unsigned int) alloc_noncontiguous;
    void (*)(struct device *, size_t, struct sg_table *, enum dma_data_direction) free_noncontiguous;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    struct page * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_pages;
    void (*)(struct device *, size_t, struct page *, dma_addr_t, enum dma_data_direction) free_pages;
    struct sg_table * (*)(struct device *, size_t, enum dma_data_direction, gfp_t, long unsigned int) alloc_noncontiguous;
    void (*)(struct device *, size_t, struct sg_table *, enum dma_data_direction) free_noncontiguous;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    unsigned int flags;
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    struct page * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_pages;
    void (*)(struct device *, size_t, struct page *, dma_addr_t, enum dma_data_direction) free_pages;
    struct sg_table * (*)(struct device *, size_t, enum dma_data_direction, gfp_t, long unsigned int) alloc_noncontiguous;
    void (*)(struct device *, size_t, struct sg_table *, enum dma_data_direction) free_noncontiguous;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    size_t (*)() opt_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    unsigned int flags;
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    struct page * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_pages;
    void (*)(struct device *, size_t, struct page *, dma_addr_t, enum dma_data_direction) free_pages;
    struct sg_table * (*)(struct device *, size_t, enum dma_data_direction, gfp_t, long unsigned int) alloc_noncontiguous;
    void (*)(struct device *, size_t, struct sg_table *, enum dma_data_direction) free_noncontiguous;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    size_t (*)() opt_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    unsigned int flags;
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    struct page * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_pages;
    void (*)(struct device *, size_t, struct page *, dma_addr_t, enum dma_data_direction) free_pages;
    struct sg_table * (*)(struct device *, size_t, enum dma_data_direction, gfp_t, long unsigned int) alloc_noncontiguous;
    void (*)(struct device *, size_t, struct sg_table *, enum dma_data_direction) free_noncontiguous;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    size_t (*)() opt_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
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
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
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
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dma_map_ops {
    void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc;
    void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free;
    int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap;
    int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable;
    dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page;
    int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg;
    dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_cpu;
    void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction) sync_single_for_device;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_cpu;
    void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction) sync_sg_for_device;
    void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync;
    int (*)(struct device *, u64) dma_supported;
    u64 (*)(struct device *) get_required_mask;
    size_t (*)(struct device *) max_mapping_size;
    long unsigned int (*)(struct device *) get_merge_boundary;
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
<b>Field type changed. </b>
<code>void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, struct dma_attrs *) alloc</code> ➡️ <code>void * (*)(struct device *, size_t, dma_addr_t *, gfp_t, long unsigned int) alloc</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct device *, size_t, void *, dma_addr_t, struct dma_attrs *) free</code> ➡️ <code>void (*)(struct device *, size_t, void *, dma_addr_t, long unsigned int) free</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, struct dma_attrs *) mmap</code> ➡️ <code>int (*)(struct device *, struct vm_area_struct *, void *, dma_addr_t, size_t, long unsigned int) mmap</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, struct dma_attrs *) get_sgtable</code> ➡️ <code>int (*)(struct device *, struct sg_table *, void *, dma_addr_t, size_t, long unsigned int) get_sgtable</code>
</li>
<li>
<b>Field type changed. </b>
<code>dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, struct dma_attrs *) map_page</code> ➡️ <code>dma_addr_t (*)(struct device *, struct page *, long unsigned int, size_t, enum dma_data_direction, long unsigned int) map_page</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, struct dma_attrs *) unmap_page</code> ➡️ <code>void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_page</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, struct dma_attrs *) map_sg</code> ➡️ <code>int (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) map_sg</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, struct dma_attrs *) unmap_sg</code> ➡️ <code>void (*)(struct device *, struct scatterlist *, int, enum dma_data_direction, long unsigned int) unmap_sg</code>
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
<code>dma_addr_t (*)(struct device *, phys_addr_t, size_t, enum dma_data_direction, long unsigned int) map_resource</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, dma_addr_t, size_t, enum dma_data_direction, long unsigned int) unmap_resource</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, u64) set_dma_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, void *, size_t, enum dma_data_direction) cache_sync</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int is_phys</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 (*)(struct device *) get_required_mask</code>
</li>
<li>
<b>Field added. </b>
<code>size_t (*)(struct device *) max_mapping_size</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, dma_addr_t) mapping_error</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int (*)(struct device *) get_merge_boundary</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct page * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_pages</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, size_t, struct page *, dma_addr_t, enum dma_data_direction) free_pages</code>
</li>
<li>
<b>Field added. </b>
<code>void * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_noncoherent</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, size_t, void *, dma_addr_t, enum dma_data_direction) free_noncoherent</code>
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
<code>struct sg_table * (*)(struct device *, size_t, enum dma_data_direction, gfp_t, long unsigned int) alloc_noncontiguous</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, size_t, struct sg_table *, enum dma_data_direction) free_noncontiguous</code>
</li>
<li>
<b>Field removed. </b>
<code>void * (*)(struct device *, size_t, dma_addr_t *, enum dma_data_direction, gfp_t) alloc_noncoherent</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct device *, size_t, void *, dma_addr_t, enum dma_data_direction) free_noncoherent</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Field added. </b>
<code>size_t (*)() opt_mapping_size</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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

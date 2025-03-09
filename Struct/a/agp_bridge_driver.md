# Struct: <code>agp_bridge_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct agp_bridge_driver {
    struct module * owner;
    const void * aperture_sizes;
    int num_aperture_sizes;
    enum aper_size_type size_type;
    bool cant_use_aperture;
    bool needs_scratch_page;
    const struct gatt_mask * masks;
    int (*)() fetch_size;
    int (*)() configure;
    void (*)(struct agp_bridge_data *, u32) agp_enable;
    void (*)() cleanup;
    void (*)(struct agp_memory *) tlb_flush;
    long unsigned int (*)(struct agp_bridge_data *, dma_addr_t, int) mask_memory;
    void (*)() cache_flush;
    int (*)(struct agp_bridge_data *) create_gatt_table;
    int (*)(struct agp_bridge_data *) free_gatt_table;
    int (*)(struct agp_memory *, off_t, int) insert_memory;
    int (*)(struct agp_memory *, off_t, int) remove_memory;
    struct agp_memory * (*)(size_t, int) alloc_by_type;
    void (*)(struct agp_memory *) free_by_type;
    struct page * (*)(struct agp_bridge_data *) agp_alloc_page;
    int (*)(struct agp_bridge_data *, struct agp_memory *, size_t) agp_alloc_pages;
    void (*)(struct page *, int) agp_destroy_page;
    void (*)(struct agp_memory *) agp_destroy_pages;
    int (*)(struct agp_bridge_data *, int) agp_type_to_mask_type;
}
```
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

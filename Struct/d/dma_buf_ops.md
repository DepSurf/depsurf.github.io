# Struct: <code>dma_buf_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    int (*)(struct dma_buf *, struct device *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, size_t, size_t, enum dma_data_direction) begin_cpu_access;
    void (*)(struct dma_buf *, size_t, size_t, enum dma_data_direction) end_cpu_access;
    void * (*)(struct dma_buf *, long unsigned int) kmap_atomic;
    void (*)(struct dma_buf *, long unsigned int, void *) kunmap_atomic;
    void * (*)(struct dma_buf *, long unsigned int) kmap;
    void (*)(struct dma_buf *, long unsigned int, void *) kunmap;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    int (*)(struct dma_buf *, struct device *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    void * (*)(struct dma_buf *, long unsigned int) kmap_atomic;
    void (*)(struct dma_buf *, long unsigned int, void *) kunmap_atomic;
    void * (*)(struct dma_buf *, long unsigned int) kmap;
    void (*)(struct dma_buf *, long unsigned int, void *) kunmap;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    int (*)(struct dma_buf *, struct device *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    void * (*)(struct dma_buf *, long unsigned int) kmap_atomic;
    void (*)(struct dma_buf *, long unsigned int, void *) kunmap_atomic;
    void * (*)(struct dma_buf *, long unsigned int) kmap;
    void (*)(struct dma_buf *, long unsigned int, void *) kunmap;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    int (*)(struct dma_buf *, struct device *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    void * (*)(struct dma_buf *, long unsigned int) map_atomic;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap_atomic;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    int (*)(struct dma_buf *, struct device *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    void * (*)(struct dma_buf *, long unsigned int) map_atomic;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap_atomic;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    int (*)(struct dma_buf *, struct device *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    void * (*)(struct dma_buf *, long unsigned int) map_atomic;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap_atomic;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    int (*)(struct dma_buf_attachment *) pin;
    void (*)(struct dma_buf_attachment *) unpin;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    int (*)(struct dma_buf_attachment *) pin;
    void (*)(struct dma_buf_attachment *) unpin;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    int (*)(struct dma_buf *, struct dma_buf_map *) vmap;
    void (*)(struct dma_buf *, struct dma_buf_map *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    int (*)(struct dma_buf_attachment *) pin;
    void (*)(struct dma_buf_attachment *) unpin;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    int (*)(struct dma_buf *, struct dma_buf_map *) vmap;
    void (*)(struct dma_buf *, struct dma_buf_map *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    int (*)(struct dma_buf_attachment *) pin;
    void (*)(struct dma_buf_attachment *) unpin;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    int (*)(struct dma_buf *, struct dma_buf_map *) vmap;
    void (*)(struct dma_buf *, struct dma_buf_map *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    int (*)(struct dma_buf_attachment *) pin;
    void (*)(struct dma_buf_attachment *) unpin;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    int (*)(struct dma_buf *, struct iosys_map *) vmap;
    void (*)(struct dma_buf *, struct iosys_map *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    int (*)(struct dma_buf_attachment *) pin;
    void (*)(struct dma_buf_attachment *) unpin;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    int (*)(struct dma_buf *, struct iosys_map *) vmap;
    void (*)(struct dma_buf *, struct iosys_map *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    int (*)(struct dma_buf_attachment *) pin;
    void (*)(struct dma_buf_attachment *) unpin;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    int (*)(struct dma_buf *, struct iosys_map *) vmap;
    void (*)(struct dma_buf *, struct iosys_map *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    int (*)(struct dma_buf_attachment *) pin;
    void (*)(struct dma_buf_attachment *) unpin;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    int (*)(struct dma_buf *, struct iosys_map *) vmap;
    void (*)(struct dma_buf *, struct iosys_map *) vunmap;
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
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
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
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dma_buf_ops {
    bool cache_sgt_mapping;
    int (*)(struct dma_buf *, struct dma_buf_attachment *) attach;
    void (*)(struct dma_buf *, struct dma_buf_attachment *) detach;
    struct sg_table * (*)(struct dma_buf_attachment *, enum dma_data_direction) map_dma_buf;
    void (*)(struct dma_buf_attachment *, struct sg_table *, enum dma_data_direction) unmap_dma_buf;
    void (*)(struct dma_buf *) release;
    int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access;
    int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access;
    int (*)(struct dma_buf *, struct vm_area_struct *) mmap;
    void * (*)(struct dma_buf *, long unsigned int) map;
    void (*)(struct dma_buf *, long unsigned int, void *) unmap;
    void * (*)(struct dma_buf *) vmap;
    void (*)(struct dma_buf *, void *) vunmap;
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
<code>int (*)(struct dma_buf *, size_t, size_t, enum dma_data_direction) begin_cpu_access</code> ➡️ <code>int (*)(struct dma_buf *, enum dma_data_direction) begin_cpu_access</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dma_buf *, size_t, size_t, enum dma_data_direction) end_cpu_access</code> ➡️ <code>int (*)(struct dma_buf *, enum dma_data_direction) end_cpu_access</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * (*)(struct dma_buf *, long unsigned int) map_atomic</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dma_buf *, long unsigned int, void *) unmap_atomic</code>
</li>
<li>
<b>Field added. </b>
<code>void * (*)(struct dma_buf *, long unsigned int) map</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dma_buf *, long unsigned int, void *) unmap</code>
</li>
<li>
<b>Field removed. </b>
<code>void * (*)(struct dma_buf *, long unsigned int) kmap_atomic</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct dma_buf *, long unsigned int, void *) kunmap_atomic</code>
</li>
<li>
<b>Field removed. </b>
<code>void * (*)(struct dma_buf *, long unsigned int) kmap</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct dma_buf *, long unsigned int, void *) kunmap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<code>void * (*)(struct dma_buf *, long unsigned int) map_atomic</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct dma_buf *, long unsigned int, void *) unmap_atomic</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dma_buf *, struct device *, struct dma_buf_attachment *) attach</code> ➡️ <code>int (*)(struct dma_buf *, struct dma_buf_attachment *) attach</code>
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
<code>bool cache_sgt_mapping</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct dma_buf_attachment *) pin</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dma_buf_attachment *) unpin</code>
</li>
<li>
<b>Field removed. </b>
<code>void * (*)(struct dma_buf *, long unsigned int) map</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct dma_buf *, long unsigned int, void *) unmap</code>
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
<code>void * (*)(struct dma_buf *) vmap</code> ➡️ <code>int (*)(struct dma_buf *, struct dma_buf_map *) vmap</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dma_buf *, void *) vunmap</code> ➡️ <code>void (*)(struct dma_buf *, struct dma_buf_map *) vunmap</code>
</li>
</ul>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dma_buf *, struct dma_buf_map *) vmap</code> ➡️ <code>int (*)(struct dma_buf *, struct iosys_map *) vmap</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dma_buf *, struct dma_buf_map *) vunmap</code> ➡️ <code>void (*)(struct dma_buf *, struct iosys_map *) vunmap</code>
</li>
</ul>
</details>
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

# Struct: <code>drm_gem_object_funcs</code>

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
struct drm_gem_object_funcs {
    void (*)(struct drm_gem_object *) free;
    int (*)(struct drm_gem_object *, struct drm_file *) open;
    void (*)(struct drm_gem_object *, struct drm_file *) close;
    void (*)(struct drm_printer *, unsigned int, const struct drm_gem_object *) print_info;
    struct dma_buf * (*)(struct drm_gem_object *, int) export;
    int (*)(struct drm_gem_object *) pin;
    void (*)(struct drm_gem_object *) unpin;
    struct sg_table * (*)(struct drm_gem_object *) get_sg_table;
    int (*)(struct drm_gem_object *, struct iosys_map *) vmap;
    void (*)(struct drm_gem_object *, struct iosys_map *) vunmap;
    int (*)(struct drm_gem_object *, struct vm_area_struct *) mmap;
    int (*)(struct drm_gem_object *) evict;
    enum drm_gem_object_status (*)(struct drm_gem_object *) status;
    size_t (*)(struct drm_gem_object *) rss;
    const struct vm_operations_struct * vm_ops;
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
struct drm_gem_object_funcs {
    void (*)(struct drm_gem_object *) free;
    int (*)(struct drm_gem_object *, struct drm_file *) open;
    void (*)(struct drm_gem_object *, struct drm_file *) close;
    void (*)(struct drm_printer *, unsigned int, const struct drm_gem_object *) print_info;
    struct dma_buf * (*)(struct drm_gem_object *, int) export;
    int (*)(struct drm_gem_object *) pin;
    void (*)(struct drm_gem_object *) unpin;
    struct sg_table * (*)(struct drm_gem_object *) get_sg_table;
    int (*)(struct drm_gem_object *, struct iosys_map *) vmap;
    void (*)(struct drm_gem_object *, struct iosys_map *) vunmap;
    int (*)(struct drm_gem_object *, struct vm_area_struct *) mmap;
    int (*)(struct drm_gem_object *) evict;
    enum drm_gem_object_status (*)(struct drm_gem_object *) status;
    size_t (*)(struct drm_gem_object *) rss;
    const struct vm_operations_struct * vm_ops;
}
```
</details>
</li>
</ul>

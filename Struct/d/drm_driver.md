# Struct: <code>drm_driver</code>

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
struct drm_driver {
    int (*)(struct drm_device *, long unsigned int) load;
    int (*)(struct drm_device *, struct drm_file *) open;
    void (*)(struct drm_device *, struct drm_file *) postclose;
    void (*)(struct drm_device *) lastclose;
    void (*)(struct drm_device *) unload;
    void (*)(struct drm_device *) release;
    void (*)(struct drm_device *, struct drm_file *, bool) master_set;
    void (*)(struct drm_device *, struct drm_file *) master_drop;
    void (*)(struct drm_minor *) debugfs_init;
    struct drm_gem_object * (*)(struct drm_device *, size_t) gem_create_object;
    int (*)(struct drm_device *, struct drm_file *, uint32_t, uint32_t, int *) prime_handle_to_fd;
    int (*)(struct drm_device *, struct drm_file *, int, uint32_t *) prime_fd_to_handle;
    struct drm_gem_object * (*)(struct drm_device *, struct dma_buf *) gem_prime_import;
    struct drm_gem_object * (*)(struct drm_device *, struct dma_buf_attachment *, struct sg_table *) gem_prime_import_sg_table;
    int (*)(struct drm_file *, struct drm_device *, struct drm_mode_create_dumb *) dumb_create;
    int (*)(struct drm_file *, struct drm_device *, uint32_t, uint64_t *) dumb_map_offset;
    void (*)(struct drm_printer *, struct drm_file *) show_fdinfo;
    int major;
    int minor;
    int patchlevel;
    char * name;
    char * desc;
    char * date;
    u32 driver_features;
    const struct drm_ioctl_desc * ioctls;
    int num_ioctls;
    const struct file_operations * fops;
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
struct drm_driver {
    int (*)(struct drm_device *, long unsigned int) load;
    int (*)(struct drm_device *, struct drm_file *) open;
    void (*)(struct drm_device *, struct drm_file *) postclose;
    void (*)(struct drm_device *) lastclose;
    void (*)(struct drm_device *) unload;
    void (*)(struct drm_device *) release;
    void (*)(struct drm_device *, struct drm_file *, bool) master_set;
    void (*)(struct drm_device *, struct drm_file *) master_drop;
    void (*)(struct drm_minor *) debugfs_init;
    struct drm_gem_object * (*)(struct drm_device *, size_t) gem_create_object;
    int (*)(struct drm_device *, struct drm_file *, uint32_t, uint32_t, int *) prime_handle_to_fd;
    int (*)(struct drm_device *, struct drm_file *, int, uint32_t *) prime_fd_to_handle;
    struct drm_gem_object * (*)(struct drm_device *, struct dma_buf *) gem_prime_import;
    struct drm_gem_object * (*)(struct drm_device *, struct dma_buf_attachment *, struct sg_table *) gem_prime_import_sg_table;
    int (*)(struct drm_file *, struct drm_device *, struct drm_mode_create_dumb *) dumb_create;
    int (*)(struct drm_file *, struct drm_device *, uint32_t, uint64_t *) dumb_map_offset;
    void (*)(struct drm_printer *, struct drm_file *) show_fdinfo;
    int major;
    int minor;
    int patchlevel;
    char * name;
    char * desc;
    char * date;
    u32 driver_features;
    const struct drm_ioctl_desc * ioctls;
    int num_ioctls;
    const struct file_operations * fops;
}
```
</details>
</li>
</ul>

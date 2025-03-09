# Struct: <code>cxl</code>

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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cxl {
    struct cxl_native * native;
    struct cxl_guest * guest;
    spinlock_t afu_list_lock;
    struct cxl_afu *[4] afu;
    struct device dev;
    struct dentry * trace;
    struct dentry * psl_err_chk;
    struct dentry * debugfs;
    char * irq_name;
    struct bin_attribute cxl_attr;
    int adapter_num;
    int user_irqs;
    u64 ps_size;
    u16 psl_rev;
    u16 base_image;
    u8 vsec_status;
    u8 caia_major;
    u8 caia_minor;
    u8 slices;
    bool user_image_loaded;
    bool perst_loads_image;
    bool perst_select_user;
    bool perst_same_image;
    bool psl_timebase_synced;
    bool tunneled_ops_supported;
    atomic_t contexts_num;
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct cxl {
    struct cxl_native * native;
    struct cxl_guest * guest;
    spinlock_t afu_list_lock;
    struct cxl_afu *[4] afu;
    struct device dev;
    struct dentry * trace;
    struct dentry * psl_err_chk;
    struct dentry * debugfs;
    char * irq_name;
    struct bin_attribute cxl_attr;
    int adapter_num;
    int user_irqs;
    u64 ps_size;
    u16 psl_rev;
    u16 base_image;
    u8 vsec_status;
    u8 caia_major;
    u8 caia_minor;
    u8 slices;
    bool user_image_loaded;
    bool perst_loads_image;
    bool perst_select_user;
    bool perst_same_image;
    bool psl_timebase_synced;
    bool tunneled_ops_supported;
    atomic_t contexts_num;
}
```
</details>
</li>
</ul>

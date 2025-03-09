# Struct: <code>cxl_backend_ops</code>

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
struct cxl_backend_ops {
    struct module * module;
    int (*)(struct cxl *) adapter_reset;
    int (*)(struct cxl *) alloc_one_irq;
    void (*)(struct cxl *, int) release_one_irq;
    int (*)(struct cxl_irq_ranges *, struct cxl *, unsigned int) alloc_irq_ranges;
    void (*)(struct cxl_irq_ranges *, struct cxl *) release_irq_ranges;
    int (*)(struct cxl *, unsigned int, unsigned int) setup_irq;
    irqreturn_t (*)(struct cxl_context *, u64, u64) handle_psl_slice_error;
    irqreturn_t (*)(int, void *) psl_interrupt;
    int (*)(struct cxl_context *, u64, u64) ack_irq;
    void (*)(struct cxl_context *) irq_wait;
    int (*)(struct cxl_context *, bool, u64, u64) attach_process;
    int (*)(struct cxl_context *) detach_process;
    void (*)(struct cxl_context *) update_ivtes;
    bool (*)(const char *, enum cxl_attrs) support_attributes;
    bool (*)(struct cxl *, struct cxl_afu *) link_ok;
    void (*)(struct device *) release_afu;
    ssize_t (*)(struct cxl_afu *, char *, loff_t, size_t) afu_read_err_buffer;
    int (*)(struct cxl_afu *) afu_check_and_enable;
    int (*)(struct cxl_afu *, int) afu_activate_mode;
    int (*)(struct cxl_afu *, int) afu_deactivate_mode;
    int (*)(struct cxl_afu *) afu_reset;
    int (*)(struct cxl_afu *, int, u64, u8 *) afu_cr_read8;
    int (*)(struct cxl_afu *, int, u64, u16 *) afu_cr_read16;
    int (*)(struct cxl_afu *, int, u64, u32 *) afu_cr_read32;
    int (*)(struct cxl_afu *, int, u64, u64 *) afu_cr_read64;
    int (*)(struct cxl_afu *, int, u64, u8) afu_cr_write8;
    int (*)(struct cxl_afu *, int, u64, u16) afu_cr_write16;
    int (*)(struct cxl_afu *, int, u64, u32) afu_cr_write32;
    ssize_t (*)(struct cxl *, void *, size_t) read_adapter_vpd;
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
struct cxl_backend_ops {
    struct module * module;
    int (*)(struct cxl *) adapter_reset;
    int (*)(struct cxl *) alloc_one_irq;
    void (*)(struct cxl *, int) release_one_irq;
    int (*)(struct cxl_irq_ranges *, struct cxl *, unsigned int) alloc_irq_ranges;
    void (*)(struct cxl_irq_ranges *, struct cxl *) release_irq_ranges;
    int (*)(struct cxl *, unsigned int, unsigned int) setup_irq;
    irqreturn_t (*)(struct cxl_context *, u64, u64) handle_psl_slice_error;
    irqreturn_t (*)(int, void *) psl_interrupt;
    int (*)(struct cxl_context *, u64, u64) ack_irq;
    void (*)(struct cxl_context *) irq_wait;
    int (*)(struct cxl_context *, bool, u64, u64) attach_process;
    int (*)(struct cxl_context *) detach_process;
    void (*)(struct cxl_context *) update_ivtes;
    bool (*)(const char *, enum cxl_attrs) support_attributes;
    bool (*)(struct cxl *, struct cxl_afu *) link_ok;
    void (*)(struct device *) release_afu;
    ssize_t (*)(struct cxl_afu *, char *, loff_t, size_t) afu_read_err_buffer;
    int (*)(struct cxl_afu *) afu_check_and_enable;
    int (*)(struct cxl_afu *, int) afu_activate_mode;
    int (*)(struct cxl_afu *, int) afu_deactivate_mode;
    int (*)(struct cxl_afu *) afu_reset;
    int (*)(struct cxl_afu *, int, u64, u8 *) afu_cr_read8;
    int (*)(struct cxl_afu *, int, u64, u16 *) afu_cr_read16;
    int (*)(struct cxl_afu *, int, u64, u32 *) afu_cr_read32;
    int (*)(struct cxl_afu *, int, u64, u64 *) afu_cr_read64;
    int (*)(struct cxl_afu *, int, u64, u8) afu_cr_write8;
    int (*)(struct cxl_afu *, int, u64, u16) afu_cr_write16;
    int (*)(struct cxl_afu *, int, u64, u32) afu_cr_write32;
    ssize_t (*)(struct cxl *, void *, size_t) read_adapter_vpd;
}
```
</details>
</li>
</ul>

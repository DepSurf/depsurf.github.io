# Struct: <code>cxl_service_layer_ops</code>

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
struct cxl_service_layer_ops {
    int (*)(struct cxl *, struct pci_dev *) adapter_regs_init;
    int (*)(struct cxl *) invalidate_all;
    int (*)(struct cxl_afu *) afu_regs_init;
    int (*)(struct cxl_afu *) sanitise_afu_regs;
    int (*)(struct cxl_afu *) register_serr_irq;
    void (*)(struct cxl_afu *) release_serr_irq;
    irqreturn_t (*)(int, struct cxl_context *, struct cxl_irq_info *) handle_interrupt;
    irqreturn_t (*)(struct cxl_afu *, struct cxl_irq_info *) fail_irq;
    int (*)(struct cxl_afu *) activate_dedicated_process;
    int (*)(struct cxl_context *, u64, u64) attach_afu_directed;
    int (*)(struct cxl_context *, u64, u64) attach_dedicated_process;
    void (*)(struct cxl_context *) update_dedicated_ivtes;
    void (*)(struct cxl *, struct dentry *) debugfs_add_adapter_regs;
    void (*)(struct cxl_afu *, struct dentry *) debugfs_add_afu_regs;
    void (*)(struct cxl_context *) psl_irq_dump_registers;
    void (*)(struct cxl *) err_irq_dump_registers;
    void (*)(struct cxl *) debugfs_stop_trace;
    void (*)(struct cxl *) write_timebase_ctrl;
    u64 (*)(struct cxl *) timebase_read;
    int capi_mode;
    bool needs_reset_before_disable;
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
struct cxl_service_layer_ops {
    int (*)(struct cxl *, struct pci_dev *) adapter_regs_init;
    int (*)(struct cxl *) invalidate_all;
    int (*)(struct cxl_afu *) afu_regs_init;
    int (*)(struct cxl_afu *) sanitise_afu_regs;
    int (*)(struct cxl_afu *) register_serr_irq;
    void (*)(struct cxl_afu *) release_serr_irq;
    irqreturn_t (*)(int, struct cxl_context *, struct cxl_irq_info *) handle_interrupt;
    irqreturn_t (*)(struct cxl_afu *, struct cxl_irq_info *) fail_irq;
    int (*)(struct cxl_afu *) activate_dedicated_process;
    int (*)(struct cxl_context *, u64, u64) attach_afu_directed;
    int (*)(struct cxl_context *, u64, u64) attach_dedicated_process;
    void (*)(struct cxl_context *) update_dedicated_ivtes;
    void (*)(struct cxl *, struct dentry *) debugfs_add_adapter_regs;
    void (*)(struct cxl_afu *, struct dentry *) debugfs_add_afu_regs;
    void (*)(struct cxl_context *) psl_irq_dump_registers;
    void (*)(struct cxl *) err_irq_dump_registers;
    void (*)(struct cxl *) debugfs_stop_trace;
    void (*)(struct cxl *) write_timebase_ctrl;
    u64 (*)(struct cxl *) timebase_read;
    int capi_mode;
    bool needs_reset_before_disable;
}
```
</details>
</li>
</ul>

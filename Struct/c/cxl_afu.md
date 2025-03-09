# Struct: <code>cxl_afu</code>

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
struct cxl_afu {
    struct cxl_afu_native * native;
    struct cxl_afu_guest * guest;
    irq_hw_number_t serr_hwirq;
    unsigned int serr_virq;
    char * psl_irq_name;
    char * err_irq_name;
    void * p2n_mmio;
    phys_addr_t psn_phys;
    u64 pp_size;
    struct cxl * adapter;
    struct device dev;
    struct cdev afu_cdev_s;
    struct cdev afu_cdev_m;
    struct cdev afu_cdev_d;
    struct device * chardev_s;
    struct device * chardev_m;
    struct device * chardev_d;
    struct idr contexts_idr;
    struct dentry * debugfs;
    struct mutex contexts_lock;
    spinlock_t afu_cntl_lock;
    atomic_t configured_state;
    u64 eb_len;
    u64 eb_offset;
    struct bin_attribute attr_eb;
    struct pci_controller * phb;
    int pp_irqs;
    int irqs_max;
    int num_procs;
    int max_procs_virtualised;
    int slice;
    int modes_supported;
    int current_mode;
    int crs_num;
    u64 crs_len;
    u64 crs_offset;
    struct list_head crs;
    enum prefault_modes prefault_mode;
    bool psa;
    bool pp_psa;
    bool enabled;
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
struct cxl_afu {
    struct cxl_afu_native * native;
    struct cxl_afu_guest * guest;
    irq_hw_number_t serr_hwirq;
    unsigned int serr_virq;
    char * psl_irq_name;
    char * err_irq_name;
    void * p2n_mmio;
    phys_addr_t psn_phys;
    u64 pp_size;
    struct cxl * adapter;
    struct device dev;
    struct cdev afu_cdev_s;
    struct cdev afu_cdev_m;
    struct cdev afu_cdev_d;
    struct device * chardev_s;
    struct device * chardev_m;
    struct device * chardev_d;
    struct idr contexts_idr;
    struct dentry * debugfs;
    struct mutex contexts_lock;
    spinlock_t afu_cntl_lock;
    atomic_t configured_state;
    u64 eb_len;
    u64 eb_offset;
    struct bin_attribute attr_eb;
    struct pci_controller * phb;
    int pp_irqs;
    int irqs_max;
    int num_procs;
    int max_procs_virtualised;
    int slice;
    int modes_supported;
    int current_mode;
    int crs_num;
    u64 crs_len;
    u64 crs_offset;
    struct list_head crs;
    enum prefault_modes prefault_mode;
    bool psa;
    bool pp_psa;
    bool enabled;
}
```
</details>
</li>
</ul>

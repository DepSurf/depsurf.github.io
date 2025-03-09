# Struct: <code>cxl_context</code>

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
struct cxl_context {
    struct cxl_afu * afu;
    phys_addr_t psn_phys;
    u64 psn_size;
    struct address_space * mapping;
    struct mutex mapping_lock;
    struct page * ff_page;
    bool mmio_err_ff;
    bool kernelapi;
    spinlock_t sste_lock;
    struct cxl_sste * sstp;
    u64 sstp0;
    u64 sstp1;
    unsigned int sst_size;
    unsigned int sst_lru;
    wait_queue_head_t wq;
    struct pid * pid;
    spinlock_t lock;
    u64 process_token;
    void * priv;
    long unsigned int * irq_bitmap;
    struct cxl_irq_ranges irqs;
    struct list_head irq_names;
    u64 fault_addr;
    u64 fault_dsisr;
    u64 afu_err;
    enum cxl_context_status status;
    struct mutex status_mutex;
    struct work_struct fault_work;
    u64 dsisr;
    u64 dar;
    struct cxl_process_element * elem;
    int pe;
    int external_pe;
    u32 irq_count;
    bool pe_inserted;
    bool master;
    bool kernel;
    bool pending_irq;
    bool pending_fault;
    bool pending_afu_err;
    struct cxl_afu_driver_ops * afu_driver_ops;
    atomic_t afu_driver_events;
    struct callback_head rcu;
    struct mm_struct * mm;
    u16 tidr;
    bool assign_tidr;
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
struct cxl_context {
    struct cxl_afu * afu;
    phys_addr_t psn_phys;
    u64 psn_size;
    struct address_space * mapping;
    struct mutex mapping_lock;
    struct page * ff_page;
    bool mmio_err_ff;
    bool kernelapi;
    spinlock_t sste_lock;
    struct cxl_sste * sstp;
    u64 sstp0;
    u64 sstp1;
    unsigned int sst_size;
    unsigned int sst_lru;
    wait_queue_head_t wq;
    struct pid * pid;
    spinlock_t lock;
    u64 process_token;
    void * priv;
    long unsigned int * irq_bitmap;
    struct cxl_irq_ranges irqs;
    struct list_head irq_names;
    u64 fault_addr;
    u64 fault_dsisr;
    u64 afu_err;
    enum cxl_context_status status;
    struct mutex status_mutex;
    struct work_struct fault_work;
    u64 dsisr;
    u64 dar;
    struct cxl_process_element * elem;
    int pe;
    int external_pe;
    u32 irq_count;
    bool pe_inserted;
    bool master;
    bool kernel;
    bool pending_irq;
    bool pending_fault;
    bool pending_afu_err;
    struct cxl_afu_driver_ops * afu_driver_ops;
    atomic_t afu_driver_events;
    struct callback_head rcu;
    struct mm_struct * mm;
    u16 tidr;
    bool assign_tidr;
}
```
</details>
</li>
</ul>

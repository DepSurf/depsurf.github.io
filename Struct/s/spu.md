# Struct: <code>spu</code>

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
struct spu {
    const char * name;
    long unsigned int local_store_phys;
    u8 * local_store;
    long unsigned int problem_phys;
    struct spu_problem * problem;
    struct spu_priv2 * priv2;
    struct list_head cbe_list;
    struct list_head full_list;
    enum (anon) alloc_state;
    int number;
    unsigned int[3] irqs;
    u32 node;
    long unsigned int flags;
    u64 class_0_pending;
    u64 class_0_dar;
    u64 class_1_dar;
    u64 class_1_dsisr;
    size_t ls_size;
    unsigned int slb_replace;
    struct mm_struct * mm;
    struct spu_context * ctx;
    struct spu_runqueue * rq;
    long long unsigned int timestamp;
    pid_t pid;
    pid_t tgid;
    spinlock_t register_lock;
    void (*)(struct spu *) wbox_callback;
    void (*)(struct spu *) ibox_callback;
    void (*)(struct spu *, int) stop_callback;
    void (*)(struct spu *) mfc_callback;
    char[8] irq_c0;
    char[8] irq_c1;
    char[8] irq_c2;
    u64 spe_id;
    void * pdata;
    struct device_node * devnode;
    struct spu_priv1 * priv1;
    u64[3] shadow_int_mask_RW;
    struct device dev;
    int has_mem_affinity;
    struct list_head aff_list;
    struct (anon) stats;
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
struct spu {
    const char * name;
    long unsigned int local_store_phys;
    u8 * local_store;
    long unsigned int problem_phys;
    struct spu_problem * problem;
    struct spu_priv2 * priv2;
    struct list_head cbe_list;
    struct list_head full_list;
    enum (anon) alloc_state;
    int number;
    unsigned int[3] irqs;
    u32 node;
    long unsigned int flags;
    u64 class_0_pending;
    u64 class_0_dar;
    u64 class_1_dar;
    u64 class_1_dsisr;
    size_t ls_size;
    unsigned int slb_replace;
    struct mm_struct * mm;
    struct spu_context * ctx;
    struct spu_runqueue * rq;
    long long unsigned int timestamp;
    pid_t pid;
    pid_t tgid;
    spinlock_t register_lock;
    void (*)(struct spu *) wbox_callback;
    void (*)(struct spu *) ibox_callback;
    void (*)(struct spu *, int) stop_callback;
    void (*)(struct spu *) mfc_callback;
    char[8] irq_c0;
    char[8] irq_c1;
    char[8] irq_c2;
    u64 spe_id;
    void * pdata;
    struct device_node * devnode;
    struct spu_priv1 * priv1;
    u64[3] shadow_int_mask_RW;
    struct device dev;
    int has_mem_affinity;
    struct list_head aff_list;
    struct (anon) stats;
}
```
</details>
</li>
</ul>

# Struct: <code>cqhci_host</code>

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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cqhci_host {
    const struct cqhci_host_ops * ops;
    void * mmio;
    struct mmc_host * mmc;
    spinlock_t lock;
    unsigned int rca;
    bool dma64;
    int num_slots;
    int qcnt;
    u32 dcmd_slot;
    u32 caps;
    u32 quirks;
    bool enabled;
    bool halted;
    bool init_done;
    bool activated;
    bool waiting_for_idle;
    bool recovery_halt;
    size_t desc_size;
    size_t data_size;
    u8 * desc_base;
    u8 slot_sz;
    u8 task_desc_len;
    u8 link_desc_len;
    u8 * trans_desc_base;
    u8 trans_desc_len;
    dma_addr_t desc_dma_base;
    dma_addr_t trans_desc_dma_base;
    struct completion halt_comp;
    wait_queue_head_t wait_queue;
    struct cqhci_slot * slot;
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct cqhci_host {
    const struct cqhci_host_ops * ops;
    void * mmio;
    struct mmc_host * mmc;
    spinlock_t lock;
    unsigned int rca;
    bool dma64;
    int num_slots;
    int qcnt;
    u32 dcmd_slot;
    u32 caps;
    u32 quirks;
    bool enabled;
    bool halted;
    bool init_done;
    bool activated;
    bool waiting_for_idle;
    bool recovery_halt;
    size_t desc_size;
    size_t data_size;
    u8 * desc_base;
    u8 slot_sz;
    u8 task_desc_len;
    u8 link_desc_len;
    u8 * trans_desc_base;
    u8 trans_desc_len;
    dma_addr_t desc_dma_base;
    dma_addr_t trans_desc_dma_base;
    struct completion halt_comp;
    wait_queue_head_t wait_queue;
    struct cqhci_slot * slot;
}
```
</details>
</li>
</ul>

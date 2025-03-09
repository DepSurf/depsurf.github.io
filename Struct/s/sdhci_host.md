# Struct: <code>sdhci_host</code>

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
struct sdhci_host {
    const char * hw_name;
    unsigned int quirks;
    unsigned int quirks2;
    int irq;
    void * ioaddr;
    char * bounce_buffer;
    dma_addr_t bounce_addr;
    unsigned int bounce_buffer_size;
    const struct sdhci_ops * ops;
    struct mmc_host * mmc;
    struct mmc_host_ops mmc_host_ops;
    u64 dma_mask;
    struct led_classdev led;
    char[32] led_name;
    spinlock_t lock;
    int flags;
    unsigned int version;
    unsigned int max_clk;
    unsigned int timeout_clk;
    unsigned int clk_mul;
    unsigned int clock;
    u8 pwr;
    bool runtime_suspended;
    bool bus_on;
    bool preset_enabled;
    bool pending_reset;
    bool irq_wake_enabled;
    bool v4_mode;
    struct mmc_request *[2] mrqs_done;
    struct mmc_command * cmd;
    struct mmc_command * data_cmd;
    struct mmc_data * data;
    unsigned int data_early;
    struct sg_mapping_iter sg_miter;
    unsigned int blocks;
    int sg_count;
    void * adma_table;
    void * align_buffer;
    size_t adma_table_sz;
    size_t align_buffer_sz;
    dma_addr_t adma_addr;
    dma_addr_t align_addr;
    unsigned int desc_sz;
    struct workqueue_struct * complete_wq;
    struct work_struct complete_work;
    struct timer_list timer;
    struct timer_list data_timer;
    u32 caps;
    u32 caps1;
    bool read_caps;
    unsigned int ocr_avail_sdio;
    unsigned int ocr_avail_sd;
    unsigned int ocr_avail_mmc;
    u32 ocr_mask;
    unsigned int timing;
    u32 thread_isr;
    u32 ier;
    bool cqe_on;
    u32 cqe_ier;
    u32 cqe_err_ier;
    wait_queue_head_t buf_ready_int;
    unsigned int tuning_done;
    unsigned int tuning_count;
    unsigned int tuning_mode;
    unsigned int tuning_err;
    int tuning_delay;
    int tuning_loop_count;
    u32 sdma_boundary;
    u32 adma_table_cnt;
    u64 data_timeout;
    long unsigned int[0] private;
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
struct sdhci_host {
    const char * hw_name;
    unsigned int quirks;
    unsigned int quirks2;
    int irq;
    void * ioaddr;
    char * bounce_buffer;
    dma_addr_t bounce_addr;
    unsigned int bounce_buffer_size;
    const struct sdhci_ops * ops;
    struct mmc_host * mmc;
    struct mmc_host_ops mmc_host_ops;
    u64 dma_mask;
    struct led_classdev led;
    char[32] led_name;
    spinlock_t lock;
    int flags;
    unsigned int version;
    unsigned int max_clk;
    unsigned int timeout_clk;
    unsigned int clk_mul;
    unsigned int clock;
    u8 pwr;
    bool runtime_suspended;
    bool bus_on;
    bool preset_enabled;
    bool pending_reset;
    bool irq_wake_enabled;
    bool v4_mode;
    struct mmc_request *[2] mrqs_done;
    struct mmc_command * cmd;
    struct mmc_command * data_cmd;
    struct mmc_data * data;
    unsigned int data_early;
    struct sg_mapping_iter sg_miter;
    unsigned int blocks;
    int sg_count;
    void * adma_table;
    void * align_buffer;
    size_t adma_table_sz;
    size_t align_buffer_sz;
    dma_addr_t adma_addr;
    dma_addr_t align_addr;
    unsigned int desc_sz;
    struct workqueue_struct * complete_wq;
    struct work_struct complete_work;
    struct timer_list timer;
    struct timer_list data_timer;
    u32 caps;
    u32 caps1;
    bool read_caps;
    unsigned int ocr_avail_sdio;
    unsigned int ocr_avail_sd;
    unsigned int ocr_avail_mmc;
    u32 ocr_mask;
    unsigned int timing;
    u32 thread_isr;
    u32 ier;
    bool cqe_on;
    u32 cqe_ier;
    u32 cqe_err_ier;
    wait_queue_head_t buf_ready_int;
    unsigned int tuning_done;
    unsigned int tuning_count;
    unsigned int tuning_mode;
    unsigned int tuning_err;
    int tuning_delay;
    int tuning_loop_count;
    u32 sdma_boundary;
    u32 adma_table_cnt;
    u64 data_timeout;
    long unsigned int[0] private;
}
```
</details>
</li>
</ul>

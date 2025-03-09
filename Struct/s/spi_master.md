# Struct: <code>spi_master</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct spi_master {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u16 mode_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_master *, struct spi_device *, struct spi_transfer *) can_dma;
    bool queued;
    struct kthread_worker kworker;
    struct task_struct * kworker_task;
    struct kthread_work pump_messages;
    spinlock_t queue_lock;
    struct list_head queue;
    struct spi_message * cur_msg;
    bool idling;
    bool busy;
    bool running;
    bool rt;
    bool auto_runtime_pm;
    bool cur_msg_prepared;
    bool cur_msg_mapped;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_master *) prepare_transfer_hardware;
    int (*)(struct spi_master *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_master *) unprepare_transfer_hardware;
    int (*)(struct spi_master *, struct spi_message *) prepare_message;
    int (*)(struct spi_master *, struct spi_message *) unprepare_message;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_master *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_master *, struct spi_message *) handle_err;
    int * cs_gpios;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct spi_master {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u16 mode_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    size_t (*)(struct spi_device *) max_transfer_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_master *, struct spi_device *, struct spi_transfer *) can_dma;
    bool queued;
    struct kthread_worker kworker;
    struct task_struct * kworker_task;
    struct kthread_work pump_messages;
    spinlock_t queue_lock;
    struct list_head queue;
    struct spi_message * cur_msg;
    bool idling;
    bool busy;
    bool running;
    bool rt;
    bool auto_runtime_pm;
    bool cur_msg_prepared;
    bool cur_msg_mapped;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_master *) prepare_transfer_hardware;
    int (*)(struct spi_master *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_master *) unprepare_transfer_hardware;
    int (*)(struct spi_master *, struct spi_message *) prepare_message;
    int (*)(struct spi_master *, struct spi_message *) unprepare_message;
    int (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_read;
    bool (*)(struct spi_device *) flash_read_supported;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_master *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_master *, struct spi_message *) handle_err;
    int * cs_gpios;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_master *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct spi_master {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u16 mode_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_master *, struct spi_device *, struct spi_transfer *) can_dma;
    bool queued;
    struct kthread_worker kworker;
    struct task_struct * kworker_task;
    struct kthread_work pump_messages;
    spinlock_t queue_lock;
    struct list_head queue;
    struct spi_message * cur_msg;
    bool idling;
    bool busy;
    bool running;
    bool rt;
    bool auto_runtime_pm;
    bool cur_msg_prepared;
    bool cur_msg_mapped;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_master *) prepare_transfer_hardware;
    int (*)(struct spi_master *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_master *) unprepare_transfer_hardware;
    int (*)(struct spi_master *, struct spi_message *) prepare_message;
    int (*)(struct spi_master *, struct spi_message *) unprepare_message;
    int (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_read;
    bool (*)(struct spi_device *) flash_read_supported;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_master *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_master *, struct spi_message *) handle_err;
    int * cs_gpios;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_master *, unsigned int) fw_translate_cs;
}
```
</details>
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>size_t (*)(struct spi_device *) max_transfer_size</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex io_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_read</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct spi_device *) flash_read_supported</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct spi_master *, unsigned int) fw_translate_cs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>size_t (*)(struct spi_device *) max_message_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct spi_master {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u16 mode_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_master *, struct spi_device *, struct spi_transfer *) can_dma;
    bool queued;
    struct kthread_worker kworker;
    struct task_struct * kworker_task;
    struct kthread_work pump_messages;
    spinlock_t queue_lock;
    struct list_head queue;
    struct spi_message * cur_msg;
    bool idling;
    bool busy;
    bool running;
    bool rt;
    bool auto_runtime_pm;
    bool cur_msg_prepared;
    bool cur_msg_mapped;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_master *) prepare_transfer_hardware;
    int (*)(struct spi_master *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_master *) unprepare_transfer_hardware;
    int (*)(struct spi_master *, struct spi_message *) prepare_message;
    int (*)(struct spi_master *, struct spi_message *) unprepare_message;
    int (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_read;
    bool (*)(struct spi_device *) flash_read_supported;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_master *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_master *, struct spi_message *) handle_err;
    int * cs_gpios;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_master *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
</ul>

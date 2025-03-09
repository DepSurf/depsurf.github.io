# Struct: <code>spi_controller</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
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
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    int (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_read;
    bool (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_can_dma;
    bool (*)(struct spi_device *) flash_read_supported;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    int * cs_gpios;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
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
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    int (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_read;
    bool (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_can_dma;
    bool (*)(struct spi_device *) flash_read_supported;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    int * cs_gpios;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
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
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
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
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    void (*)(struct spi_device *, u8, u8, u8) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    void (*)(struct spi_device *, u8, u8, u8) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_delay *, struct spi_delay *, struct spi_delay *) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    struct spi_delay cs_setup;
    struct spi_delay cs_hold;
    struct spi_delay cs_inactive;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    u8 unused_native_cs;
    u8 max_native_cs;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
    bool ptp_sts_supported;
    long unsigned int irq_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_delay *, struct spi_delay *, struct spi_delay *) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
    bool queued;
    struct kthread_worker * kworker;
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
    bool last_cs_enable;
    bool last_cs_mode_high;
    bool fallback;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    struct spi_delay cs_setup;
    struct spi_delay cs_hold;
    struct spi_delay cs_inactive;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    u8 unused_native_cs;
    u8 max_native_cs;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
    bool ptp_sts_supported;
    long unsigned int irq_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool devm_allocated;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_delay *, struct spi_delay *, struct spi_delay *) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
    bool queued;
    struct kthread_worker * kworker;
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
    bool last_cs_enable;
    bool last_cs_mode_high;
    bool fallback;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    struct spi_delay cs_setup;
    struct spi_delay cs_hold;
    struct spi_delay cs_inactive;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    s8 unused_native_cs;
    s8 max_native_cs;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
    bool ptp_sts_supported;
    long unsigned int irq_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool devm_allocated;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    struct mutex add_lock;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
    struct device * dma_map_dev;
    bool queued;
    struct kthread_worker * kworker;
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
    bool last_cs_enable;
    bool last_cs_mode_high;
    bool fallback;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    s8 unused_native_cs;
    s8 max_native_cs;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
    bool ptp_sts_supported;
    long unsigned int irq_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool devm_allocated;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    struct mutex add_lock;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
    struct device * dma_map_dev;
    bool queued;
    struct kthread_worker * kworker;
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
    char last_cs;
    bool last_cs_mode_high;
    bool fallback;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    const struct spi_controller_mem_caps * mem_caps;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    s8 unused_native_cs;
    s8 max_native_cs;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
    bool ptp_sts_supported;
    long unsigned int irq_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool devm_allocated;
    bool slave;
    bool target;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    struct mutex add_lock;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
    struct device * dma_map_dev;
    struct device * cur_rx_dma_dev;
    struct device * cur_tx_dma_dev;
    bool queued;
    struct kthread_worker * kworker;
    struct kthread_work pump_messages;
    spinlock_t queue_lock;
    struct list_head queue;
    struct spi_message * cur_msg;
    struct completion cur_msg_completion;
    bool cur_msg_incomplete;
    bool cur_msg_need_completion;
    bool busy;
    bool running;
    bool rt;
    bool auto_runtime_pm;
    bool cur_msg_mapped;
    char last_cs;
    bool last_cs_mode_high;
    bool fallback;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    int (*)(struct spi_controller *) target_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    const struct spi_controller_mem_caps * mem_caps;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    s8 unused_native_cs;
    s8 max_native_cs;
    struct spi_statistics * pcpu_statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
    bool ptp_sts_supported;
    long unsigned int irq_flags;
    bool queue_empty;
    bool must_async;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool devm_allocated;
    bool slave;
    bool target;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    struct mutex add_lock;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
    struct device * dma_map_dev;
    struct device * cur_rx_dma_dev;
    struct device * cur_tx_dma_dev;
    bool queued;
    struct kthread_worker * kworker;
    struct kthread_work pump_messages;
    spinlock_t queue_lock;
    struct list_head queue;
    struct spi_message * cur_msg;
    struct completion cur_msg_completion;
    bool cur_msg_incomplete;
    bool cur_msg_need_completion;
    bool busy;
    bool running;
    bool rt;
    bool auto_runtime_pm;
    bool cur_msg_mapped;
    char last_cs;
    bool last_cs_mode_high;
    bool fallback;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    int (*)(struct spi_controller *) target_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    const struct spi_controller_mem_caps * mem_caps;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    s8 unused_native_cs;
    s8 max_native_cs;
    struct spi_statistics * pcpu_statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
    bool ptp_sts_supported;
    long unsigned int irq_flags;
    bool queue_empty;
    bool must_async;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool devm_allocated;
    bool slave;
    bool target;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    struct mutex add_lock;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
    struct device * dma_map_dev;
    struct device * cur_rx_dma_dev;
    struct device * cur_tx_dma_dev;
    bool queued;
    struct kthread_worker * kworker;
    struct kthread_work pump_messages;
    spinlock_t queue_lock;
    struct list_head queue;
    struct spi_message * cur_msg;
    struct completion cur_msg_completion;
    bool cur_msg_incomplete;
    bool cur_msg_need_completion;
    bool busy;
    bool running;
    bool rt;
    bool auto_runtime_pm;
    bool cur_msg_mapped;
    char[16] last_cs;
    char last_cs_index_mask;
    bool last_cs_mode_high;
    bool fallback;
    struct completion xfer_completion;
    size_t max_dma_len;
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    int (*)(struct spi_controller *) target_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    const struct spi_controller_mem_caps * mem_caps;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    s8 unused_native_cs;
    s8 max_native_cs;
    struct spi_statistics * pcpu_statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
    bool ptp_sts_supported;
    long unsigned int irq_flags;
    bool queue_empty;
    bool must_async;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    void (*)(struct spi_device *, u8, u8, u8) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    void (*)(struct spi_device *, u8, u8, u8) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    void (*)(struct spi_device *, u8, u8, u8) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    void (*)(struct spi_device *, u8, u8, u8) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    void (*)(struct spi_device *, u8, u8, u8) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    void (*)(struct spi_device *, u8, u8, u8) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    void (*)(struct spi_device *, u8, u8, u8) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct spi_controller {
    struct device dev;
    struct list_head list;
    s16 bus_num;
    u16 num_chipselect;
    u16 dma_alignment;
    u32 mode_bits;
    u32 buswidth_override_bits;
    u32 bits_per_word_mask;
    u32 min_speed_hz;
    u32 max_speed_hz;
    u16 flags;
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    void (*)(struct spi_device *, u8, u8, u8) set_cs_timing;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    const struct spi_controller_mem_ops * mem_ops;
    int * cs_gpios;
    struct gpio_desc * * cs_gpiods;
    bool use_gpio_descriptors;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct spi_controller {
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
    bool slave;
    size_t (*)(struct spi_device *) max_transfer_size;
    size_t (*)(struct spi_device *) max_message_size;
    struct mutex io_mutex;
    spinlock_t bus_lock_spinlock;
    struct mutex bus_lock_mutex;
    bool bus_lock_flag;
    int (*)(struct spi_device *) setup;
    int (*)(struct spi_device *, struct spi_message *) transfer;
    void (*)(struct spi_device *) cleanup;
    bool (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) can_dma;
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
    int (*)(struct spi_controller *) prepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) transfer_one_message;
    int (*)(struct spi_controller *) unprepare_transfer_hardware;
    int (*)(struct spi_controller *, struct spi_message *) prepare_message;
    int (*)(struct spi_controller *, struct spi_message *) unprepare_message;
    int (*)(struct spi_controller *) slave_abort;
    int (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_read;
    bool (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_can_dma;
    bool (*)(struct spi_device *) flash_read_supported;
    void (*)(struct spi_device *, bool) set_cs;
    int (*)(struct spi_controller *, struct spi_device *, struct spi_transfer *) transfer_one;
    void (*)(struct spi_controller *, struct spi_message *) handle_err;
    int * cs_gpios;
    struct spi_statistics statistics;
    struct dma_chan * dma_tx;
    struct dma_chan * dma_rx;
    void * dummy_rx;
    void * dummy_tx;
    int (*)(struct spi_controller *, unsigned int) fw_translate_cs;
}
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct spi_controller_mem_ops * mem_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_read</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct spi_device *, struct spi_flash_read_message *) spi_flash_can_dma</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct spi_device *) flash_read_supported</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct spi_device *, u8, u8, u8) set_cs_timing</code>
</li>
<li>
<b>Field added. </b>
<code>struct gpio_desc * * cs_gpiods</code>
</li>
<li>
<b>Field added. </b>
<code>bool use_gpio_descriptors</code>
</li>
<li>
<b>Field type changed. </b>
<code>u16 mode_bits</code> ➡️ <code>u32 mode_bits</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 buswidth_override_bits</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct spi_delay cs_setup</code>
</li>
<li>
<b>Field added. </b>
<code>struct spi_delay cs_hold</code>
</li>
<li>
<b>Field added. </b>
<code>struct spi_delay cs_inactive</code>
</li>
<li>
<b>Field added. </b>
<code>u8 unused_native_cs</code>
</li>
<li>
<b>Field added. </b>
<code>u8 max_native_cs</code>
</li>
<li>
<b>Field added. </b>
<code>bool ptp_sts_supported</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int irq_flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct spi_device *, u8, u8, u8) set_cs_timing</code> ➡️ <code>int (*)(struct spi_device *, struct spi_delay *, struct spi_delay *, struct spi_delay *) set_cs_timing</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool last_cs_enable</code>
</li>
<li>
<b>Field added. </b>
<code>bool last_cs_mode_high</code>
</li>
<li>
<b>Field added. </b>
<code>bool fallback</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_struct * kworker_task</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct kthread_worker kworker</code> ➡️ <code>struct kthread_worker * kworker</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool devm_allocated</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 unused_native_cs</code> ➡️ <code>s8 unused_native_cs</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 max_native_cs</code> ➡️ <code>s8 max_native_cs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex add_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct device * dma_map_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct spi_delay cs_setup</code>
</li>
<li>
<b>Field removed. </b>
<code>struct spi_delay cs_hold</code>
</li>
<li>
<b>Field removed. </b>
<code>struct spi_delay cs_inactive</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct spi_device *, struct spi_delay *, struct spi_delay *, struct spi_delay *) set_cs_timing</code> ➡️ <code>int (*)(struct spi_device *) set_cs_timing</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>char last_cs</code>
</li>
<li>
<b>Field added. </b>
<code>const struct spi_controller_mem_caps * mem_caps</code>
</li>
<li>
<b>Field removed. </b>
<code>bool last_cs_enable</code>
</li>
<li>
<b>Field removed. </b>
<code>int * cs_gpios</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool target</code>
</li>
<li>
<b>Field added. </b>
<code>struct device * cur_rx_dma_dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct device * cur_tx_dma_dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion cur_msg_completion</code>
</li>
<li>
<b>Field added. </b>
<code>bool cur_msg_incomplete</code>
</li>
<li>
<b>Field added. </b>
<code>bool cur_msg_need_completion</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct spi_controller *) target_abort</code>
</li>
<li>
<b>Field added. </b>
<code>struct spi_statistics * pcpu_statistics</code>
</li>
<li>
<b>Field added. </b>
<code>bool queue_empty</code>
</li>
<li>
<b>Field added. </b>
<code>bool must_async</code>
</li>
<li>
<b>Field removed. </b>
<code>bool idling</code>
</li>
<li>
<b>Field removed. </b>
<code>bool cur_msg_prepared</code>
</li>
<li>
<b>Field removed. </b>
<code>struct spi_statistics statistics</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>char last_cs_index_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>char last_cs</code> ➡️ <code>char[16] last_cs</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

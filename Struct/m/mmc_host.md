# Struct: <code>mmc_host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct task_struct * claimer;
    int claim_cnt;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_async_req * areq;
    struct mmc_context_info context_info;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct task_struct * claimer;
    int claim_cnt;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_async_req * areq;
    struct mmc_context_info context_info;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct task_struct * claimer;
    int claim_cnt;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_async_req * areq;
    struct mmc_context_info context_info;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct task_struct * claimer;
    int claim_cnt;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_async_req * areq;
    struct mmc_context_info context_info;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_async_req * areq;
    struct mmc_context_info context_info;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    bool hsq_enabled;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    struct wakeup_source * ws;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int doing_init_tune;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    bool hsq_enabled;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct wakeup_source * ws;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int doing_init_tune;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    struct blk_keyslot_manager ksm;
    bool hsq_enabled;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct wakeup_source * ws;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int doing_init_tune;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    struct blk_keyslot_manager ksm;
    bool hsq_enabled;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct wakeup_source * ws;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int doing_init_tune;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    struct blk_crypto_profile crypto_profile;
    bool hsq_enabled;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct wakeup_source * ws;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int doing_init_tune;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct work_struct sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    struct blk_crypto_profile crypto_profile;
    bool hsq_enabled;
    u32[15] err_stats;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct wakeup_source * ws;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int doing_init_tune;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    unsigned int vqmmc_enabled;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct work_struct sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    struct blk_crypto_profile crypto_profile;
    bool hsq_enabled;
    u32[15] err_stats;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct wakeup_source * ws;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int doing_init_tune;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    unsigned int vqmmc_enabled;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct work_struct sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    struct blk_crypto_profile crypto_profile;
    bool hsq_enabled;
    int hsq_depth;
    u32[15] err_stats;
    long unsigned int[0] private;
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
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
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
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int retune_paused</code>
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
<code>struct mmc_request * ongoing_mrq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct delayed_work sdio_irq_work</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int fixed_drv_type</code>
</li>
<li>
<b>Field added. </b>
<code>struct mmc_ctx default_ctx</code>
</li>
<li>
<b>Field added. </b>
<code>const struct mmc_cqe_ops * cqe_ops</code>
</li>
<li>
<b>Field added. </b>
<code>void * cqe_private</code>
</li>
<li>
<b>Field added. </b>
<code>int cqe_qdepth</code>
</li>
<li>
<b>Field added. </b>
<code>bool cqe_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>bool cqe_on</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct task_struct * claimer</code> ➡️ <code>struct mmc_ctx * claimer</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int use_blk_mq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mmc_async_req * areq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mmc_context_info context_info</code>
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
<code>unsigned int retune_crc_disable</code>
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
<code>unsigned int can_dma_map_merge</code>
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
<code>bool hsq_enabled</code>
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
<code>struct wakeup_source * ws</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int doing_init_tune</code>
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
<code>struct blk_keyslot_manager ksm</code>
</li>
<li>
<b>Field removed. </b>
<code>struct notifier_block pm_notify</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int bus_dead</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int use_blk_mq</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int bus_refs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct blk_crypto_profile crypto_profile</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_keyslot_manager ksm</code>
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
<code>u32[15] err_stats</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct delayed_work sdio_irq_work</code> ➡️ <code>struct work_struct sdio_irq_work</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int vqmmc_enabled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int hsq_depth</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct notifier_block pm_notify</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct mmc_host {
    struct device * parent;
    struct device class_dev;
    int index;
    const struct mmc_host_ops * ops;
    struct mmc_pwrseq * pwrseq;
    unsigned int f_min;
    unsigned int f_max;
    unsigned int f_init;
    u32 ocr_avail;
    u32 ocr_avail_sdio;
    u32 ocr_avail_sd;
    u32 ocr_avail_mmc;
    struct notifier_block pm_notify;
    u32 max_current_330;
    u32 max_current_300;
    u32 max_current_180;
    u32 caps;
    u32 caps2;
    int fixed_drv_type;
    mmc_pm_flag_t pm_caps;
    unsigned int max_seg_size;
    short unsigned int max_segs;
    short unsigned int unused;
    unsigned int max_req_size;
    unsigned int max_blk_size;
    unsigned int max_blk_count;
    unsigned int max_busy_timeout;
    spinlock_t lock;
    struct mmc_ios ios;
    unsigned int use_spi_crc;
    unsigned int claimed;
    unsigned int bus_dead;
    unsigned int can_retune;
    unsigned int doing_retune;
    unsigned int retune_now;
    unsigned int retune_paused;
    unsigned int use_blk_mq;
    unsigned int retune_crc_disable;
    unsigned int can_dma_map_merge;
    int rescan_disable;
    int rescan_entered;
    int need_retune;
    int hold_retune;
    unsigned int retune_period;
    struct timer_list retune_timer;
    bool trigger_card_event;
    struct mmc_card * card;
    wait_queue_head_t wq;
    struct mmc_ctx * claimer;
    int claim_cnt;
    struct mmc_ctx default_ctx;
    struct delayed_work detect;
    int detect_change;
    struct mmc_slot slot;
    const struct mmc_bus_ops * bus_ops;
    unsigned int bus_refs;
    unsigned int sdio_irqs;
    struct task_struct * sdio_irq_thread;
    struct delayed_work sdio_irq_work;
    bool sdio_irq_pending;
    atomic_t sdio_irq_thread_abort;
    mmc_pm_flag_t pm_flags;
    struct led_trigger * led;
    bool regulator_enabled;
    struct mmc_supply supply;
    struct dentry * debugfs_root;
    struct mmc_request * ongoing_mrq;
    unsigned int actual_clock;
    unsigned int slotno;
    int dsr_req;
    u32 dsr;
    const struct mmc_cqe_ops * cqe_ops;
    void * cqe_private;
    int cqe_qdepth;
    bool cqe_enabled;
    bool cqe_on;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

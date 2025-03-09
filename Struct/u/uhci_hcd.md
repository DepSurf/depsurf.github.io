# Struct: <code>uhci_hcd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
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
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
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
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
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
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int is_aspeed</code>
</li>
</ul>
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
<code>struct clk * clk</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct dentry * dentry</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct clk * clk</code> ➡️ <code>struct clk * clk</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct uhci_hcd {
    struct dentry * dentry;
    long unsigned int io_addr;
    void * regs;
    struct dma_pool * qh_pool;
    struct dma_pool * td_pool;
    struct uhci_td * term_td;
    struct uhci_qh *[11] skelqh;
    struct uhci_qh * next_qh;
    spinlock_t lock;
    dma_addr_t frame_dma_handle;
    __le32 * frame;
    void * * frame_cpu;
    enum uhci_rh_state rh_state;
    long unsigned int auto_stop_time;
    unsigned int frame_number;
    unsigned int is_stopped;
    unsigned int last_iso_frame;
    unsigned int cur_iso_frame;
    unsigned int scan_in_progress;
    unsigned int need_rescan;
    unsigned int dead;
    unsigned int RD_enable;
    unsigned int is_initialized;
    unsigned int fsbr_is_on;
    unsigned int fsbr_is_wanted;
    unsigned int fsbr_expiring;
    struct timer_list fsbr_timer;
    unsigned int oc_low;
    unsigned int wait_for_hp;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int is_aspeed;
    long unsigned int port_c_suspend;
    long unsigned int resuming_ports;
    long unsigned int ports_timeout;
    struct list_head idle_qh_list;
    int rh_numports;
    wait_queue_head_t waitqh;
    int num_waiting;
    int total_load;
    short int[32] load;
    struct clk * clk;
    void (*)(struct uhci_hcd *) reset_hc;
    int (*)(struct uhci_hcd *) check_and_reset_hc;
    void (*)(struct uhci_hcd *) configure_hc;
    int (*)(struct uhci_hcd *) resume_detect_interrupts_are_broken;
    int (*)(struct uhci_hcd *) global_suspend_mode_is_broken;
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

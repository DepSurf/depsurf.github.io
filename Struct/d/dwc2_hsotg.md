# Struct: <code>dwc2_hsotg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params * core_params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    u32 phyif;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    u16 periodic_usecs;
    u16[8] frame_usecs;
    u16 frame_number;
    u16 periodic_qh_count;
    bool bus_suspended;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params * core_params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    u32 phyif;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 frame_number;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    u32 phyif;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 frame_number;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    u32 phyif;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 frame_number;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    u32 phyif;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 frame_number;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    u32 phyif;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    u32 phyif;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    struct regulator * usb33d;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    struct usb_role_switch * role_sw;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    struct regulator * usb33d;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    struct usb_role_switch * role_sw;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int in_ppd;
    bool bus_suspended;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    struct regulator * usb33d;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    struct usb_role_switch * role_sw;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int in_ppd;
    bool bus_suspended;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    struct regulator * usb33d;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    struct usb_role_switch * role_sw;
    enum usb_dr_mode role_sw_default_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int in_ppd;
    bool bus_suspended;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    struct regulator * usb33d;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    struct usb_role_switch * role_sw;
    enum usb_dr_mode role_sw_default_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int in_ppd;
    bool bus_suspended;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    struct regulator * usb33d;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    struct usb_role_switch * role_sw;
    enum usb_dr_mode role_sw_default_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int in_ppd;
    bool bus_suspended;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    struct regulator * usb33d;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct clk * utmi_clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    struct usb_role_switch * role_sw;
    enum usb_dr_mode role_sw_default_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int in_ppd;
    bool bus_suspended;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    struct regulator * usb33d;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct clk * utmi_clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
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
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[25] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
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
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
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
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
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
<code>struct reset_control * reset</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head split_order</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[13] hs_periodic_bitmap</code>
</li>
<li>
<b>Field added. </b>
<code>bool new_connection</code>
</li>
<li>
<b>Field added. </b>
<code>u16 last_frame_num</code>
</li>
<li>
<b>Field added. </b>
<code>u32 frame_list_sz</code>
</li>
<li>
<b>Field added. </b>
<code>struct kmem_cache * desc_gen_cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct kmem_cache * desc_hsisoc_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>u16[8] frame_usecs</code>
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
<code>struct dwc2_core_params params</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dwc2_core_params * core_params</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<code>unsigned int hibernated</code>
</li>
<li>
<b>Field added. </b>
<code>struct regulator * vbus_supply</code>
</li>
<li>
<b>Field added. </b>
<code>struct reset_control * reset_ecc</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head non_periodic_sched_waiting</code>
</li>
<li>
<b>Field added. </b>
<code>struct kmem_cache * unaligned_cache</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool needs_byte_swap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int reset_phy_on_wake</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int need_phy_for_wake</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int phy_off_for_suspend</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct phy_reset_work</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 phyif</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct regulator * usb33d</code>
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
<code>struct usb_role_switch * role_sw</code>
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
<code>unsigned int in_ppd</code>
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
<code>enum usb_dr_mode role_sw_default_mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct clk * utmi_clk</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[13] hs_periodic_bitmap</code> ➡️ <code>long unsigned int[25] hs_periodic_bitmap</code>
</li>
</ul>
</details>
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
struct dwc2_hsotg {
    struct device * dev;
    void * regs;
    struct dwc2_hw_params hw_params;
    struct dwc2_core_params params;
    enum usb_otg_state op_state;
    enum usb_dr_mode dr_mode;
    unsigned int hcd_enabled;
    unsigned int gadget_enabled;
    unsigned int ll_hw_enabled;
    unsigned int hibernated;
    unsigned int reset_phy_on_wake;
    unsigned int need_phy_for_wake;
    unsigned int phy_off_for_suspend;
    u16 frame_number;
    struct phy * phy;
    struct usb_phy * uphy;
    struct dwc2_hsotg_plat * plat;
    struct regulator_bulk_data[2] supplies;
    struct regulator * vbus_supply;
    spinlock_t lock;
    void * priv;
    int irq;
    struct clk * clk;
    struct reset_control * reset;
    struct reset_control * reset_ecc;
    unsigned int queuing_high_bandwidth;
    unsigned int srp_success;
    struct workqueue_struct * wq_otg;
    struct work_struct wf_otg;
    struct timer_list wkp_timer;
    enum dwc2_lx_state lx_state;
    struct dwc2_gregs_backup gr_backup;
    struct dwc2_dregs_backup dr_backup;
    struct dwc2_hregs_backup hr_backup;
    struct dentry * debug_root;
    struct debugfs_regset32 * regset;
    bool needs_byte_swap;
    union dwc2_hcd_internal_flags flags;
    struct list_head non_periodic_sched_inactive;
    struct list_head non_periodic_sched_waiting;
    struct list_head non_periodic_sched_active;
    struct list_head * non_periodic_qh_ptr;
    struct list_head periodic_sched_inactive;
    struct list_head periodic_sched_ready;
    struct list_head periodic_sched_assigned;
    struct list_head periodic_sched_queued;
    struct list_head split_order;
    u16 periodic_usecs;
    long unsigned int[13] hs_periodic_bitmap;
    u16 periodic_qh_count;
    bool bus_suspended;
    bool new_connection;
    u16 last_frame_num;
    struct list_head free_hc_list;
    int periodic_channels;
    int non_periodic_channels;
    int available_host_channels;
    struct dwc2_host_chan *[16] hc_ptr_array;
    u8 * status_buf;
    dma_addr_t status_buf_dma;
    struct delayed_work start_work;
    struct delayed_work reset_work;
    struct work_struct phy_reset_work;
    u8 otg_port;
    u32 * frame_list;
    dma_addr_t frame_list_dma;
    u32 frame_list_sz;
    struct kmem_cache * desc_gen_cache;
    struct kmem_cache * desc_hsisoc_cache;
    struct kmem_cache * unaligned_cache;
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

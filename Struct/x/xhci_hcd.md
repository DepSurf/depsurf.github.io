# Struct: <code>xhci_hcd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    int event_ring_max;
    int addr_64;
    int page_size;
    int page_shift;
    int msix_count;
    struct msix_entry * msix_entries;
    struct clk * clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct timer_list cmd_timer;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct completion addr_dev;
    int slot_id;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    int error_bitmask;
    unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_bus_state[2] bus_state;
    u8 * port_array;
    __le32 * * usb3_ports;
    unsigned int num_usb3_ports;
    __le32 * * usb2_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int num_usb2_ports;
    unsigned int sw_lpm_support;
    unsigned int hw_lpm_support;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    int event_ring_max;
    int addr_64;
    int page_size;
    int page_shift;
    int msix_count;
    struct msix_entry * msix_entries;
    struct clk * clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct timer_list cmd_timer;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct completion addr_dev;
    int slot_id;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    int error_bitmask;
    unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_bus_state[2] bus_state;
    u8 * port_array;
    __le32 * * usb3_ports;
    unsigned int num_usb3_ports;
    __le32 * * usb2_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int num_usb2_ports;
    unsigned int sw_lpm_support;
    unsigned int hw_lpm_support;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    int event_ring_max;
    int addr_64;
    int page_size;
    int page_shift;
    int msix_count;
    struct msix_entry * msix_entries;
    struct clk * clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_bus_state[2] bus_state;
    u8 * port_array;
    __le32 * * usb3_ports;
    unsigned int num_usb3_ports;
    __le32 * * usb2_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int num_usb2_ports;
    unsigned int sw_lpm_support;
    unsigned int hw_lpm_support;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_bus_state[2] bus_state;
    u8 * port_array;
    __le32 * * usb3_ports;
    unsigned int num_usb3_ports;
    __le32 * * usb2_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int num_usb2_ports;
    unsigned int sw_lpm_support;
    unsigned int hw_lpm_support;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_bus_state[2] bus_state;
    u8 * port_array;
    __le32 * * usb3_ports;
    unsigned int num_usb3_ports;
    __le32 * * usb2_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int num_usb2_ports;
    unsigned int sw_lpm_support;
    unsigned int hw_lpm_support;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_bus_state[2] bus_state;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int sw_lpm_support;
    unsigned int hw_lpm_support;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct reset_control * reset;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct reset_control * reset;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    u32 isoc_bei_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct reset_control * reset;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    u32 isoc_bei_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct reset_control * reset;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    unsigned int allow_single_roothub;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    u32 isoc_bei_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct reset_control * reset;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct mutex mutex;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    long unsigned int run_graceperiod;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    unsigned int allow_single_roothub;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u16 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    u32 isoc_bei_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct reset_control * reset;
    struct xhci_device_context_array * dcbaa;
    struct xhci_interrupter * interrupter;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_scratchpad * scratchpad;
    struct mutex mutex;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    long unsigned int run_graceperiod;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    unsigned int allow_single_roothub;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u16 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    u32 isoc_bei_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int nvecs;
    struct clk * clk;
    struct clk * reg_clk;
    struct reset_control * reset;
    struct xhci_device_context_array * dcbaa;
    struct xhci_interrupter * * interrupters;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_scratchpad * scratchpad;
    struct mutex mutex;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    long unsigned int run_graceperiod;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    unsigned int allow_single_roothub;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
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
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
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
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xhci_hcd {
    struct usb_hcd * main_hcd;
    struct usb_hcd * shared_hcd;
    struct xhci_cap_regs * cap_regs;
    struct xhci_op_regs * op_regs;
    struct xhci_run_regs * run_regs;
    struct xhci_doorbell_array * dba;
    struct xhci_intr_reg * ir_set;
    __u32 hcs_params1;
    __u32 hcs_params2;
    __u32 hcs_params3;
    __u32 hcc_params;
    __u32 hcc_params2;
    spinlock_t lock;
    u8 sbrn;
    u16 hci_version;
    u8 max_slots;
    u8 max_interrupters;
    u8 max_ports;
    u8 isoc_threshold;
    u32 imod_interval;
    int event_ring_max;
    int page_size;
    int page_shift;
    int msix_count;
    struct clk * clk;
    struct clk * reg_clk;
    struct xhci_device_context_array * dcbaa;
    struct xhci_ring * cmd_ring;
    unsigned int cmd_ring_state;
    struct list_head cmd_list;
    unsigned int cmd_ring_reserved_trbs;
    struct delayed_work cmd_timer;
    struct completion cmd_ring_stop_completion;
    struct xhci_command * current_cmd;
    struct xhci_ring * event_ring;
    struct xhci_erst erst;
    struct xhci_scratchpad * scratchpad;
    struct list_head lpm_failed_devs;
    struct mutex mutex;
    struct xhci_command * lpm_command;
    struct xhci_virt_device *[256] devs;
    struct xhci_root_port_bw_info * rh_bw;
    struct dma_pool * device_pool;
    struct dma_pool * segment_pool;
    struct dma_pool * small_streams_pool;
    struct dma_pool * medium_streams_pool;
    unsigned int xhc_state;
    u32 command;
    struct s3_save s3;
    long long unsigned int quirks;
    unsigned int num_active_eps;
    unsigned int limit_active_eps;
    struct xhci_port * hw_ports;
    struct xhci_hub usb2_rhub;
    struct xhci_hub usb3_rhub;
    unsigned int hw_lpm_support;
    unsigned int broken_suspend;
    u32 * ext_caps;
    unsigned int num_ext_caps;
    struct xhci_port_cap * port_caps;
    unsigned int num_port_caps;
    struct timer_list comp_mode_recovery_timer;
    u32 port_status_u0;
    u16 test_mode;
    struct dentry * debugfs_root;
    struct dentry * debugfs_slots;
    struct list_head regset_list;
    void * dbc;
    long unsigned int[0] priv;
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
<code>long unsigned int[0] priv</code>
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
<code>struct completion cmd_ring_stop_completion</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion addr_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>int slot_id</code>
</li>
<li>
<b>Field removed. </b>
<code>int error_bitmask</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct timer_list cmd_timer</code> ➡️ <code>struct delayed_work cmd_timer</code>
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
<code>u16 test_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>int addr_64</code>
</li>
<li>
<b>Field removed. </b>
<code>struct msix_entry * msix_entries</code>
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
<code>struct dentry * debugfs_root</code>
</li>
<li>
<b>Field added. </b>
<code>struct dentry * debugfs_slots</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head regset_list</code>
</li>
<li>
<b>Field added. </b>
<code>void * dbc</code>
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
<code>u32 imod_interval</code>
</li>
<li>
<b>Field added. </b>
<code>struct clk * reg_clk</code>
</li>
<li>
<b>Field added. </b>
<code>struct xhci_port * hw_ports</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 * port_array</code>
</li>
<li>
<b>Field removed. </b>
<code>__le32 * * usb3_ports</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num_usb3_ports</code>
</li>
<li>
<b>Field removed. </b>
<code>__le32 * * usb2_ports</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num_usb2_ports</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int quirks</code> ➡️ <code>long long unsigned int quirks</code>
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
<code>unsigned int broken_suspend</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xhci_bus_state[2] bus_state</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sw_lpm_support</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xhci_port_cap * port_caps</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_port_caps</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct reset_control * reset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 isoc_bei_interval</code>
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
<code>unsigned int allow_single_roothub</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xhci_command * lpm_command</code>
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
<code>long unsigned int run_graceperiod</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head lpm_failed_devs</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 command</code>
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
<code>struct xhci_interrupter * interrupter</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xhci_intr_reg * ir_set</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xhci_ring * event_ring</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xhci_erst erst</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 max_interrupters</code> ➡️ <code>u16 max_interrupters</code>
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
<code>int nvecs</code>
</li>
<li>
<b>Field added. </b>
<code>struct xhci_interrupter * * interrupters</code>
</li>
<li>
<b>Field removed. </b>
<code>int msix_count</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xhci_interrupter * interrupter</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct clk * clk</code> ➡️ <code>struct clk * clk</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct clk * reg_clk</code> ➡️ <code>struct clk * reg_clk</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

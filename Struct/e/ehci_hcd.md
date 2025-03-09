# Struct: <code>ehci_hcd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[11] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    unsigned int spurious_oc;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    unsigned int spurious_oc;
    unsigned int is_aspeed;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    unsigned int spurious_oc;
    unsigned int is_aspeed;
    unsigned int zx_wakeup_clear_needed;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    unsigned int spurious_oc;
    unsigned int is_aspeed;
    unsigned int zx_wakeup_clear_needed;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    unsigned int spurious_oc;
    unsigned int is_aspeed;
    unsigned int zx_wakeup_clear_needed;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int has_ci_pec_bug;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    unsigned int spurious_oc;
    unsigned int is_aspeed;
    unsigned int zx_wakeup_clear_needed;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
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
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
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
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
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
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
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
<code>__le32 old_current</code>
</li>
<li>
<b>Field added. </b>
<code>__le32 old_token</code>
</li>
<li>
<b>Field type changed. </b>
<code>ktime_t[11] hr_timeouts</code> ➡️ <code>ktime_t[12] hr_timeouts</code>
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
<code>unsigned int has_fsl_susp_errata</code>
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<b>Field added. </b>
<code>unsigned int spurious_oc</code>
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
<code>unsigned int is_aspeed</code>
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
<code>unsigned int zx_wakeup_clear_needed</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
<code>unsigned int has_ci_pec_bug</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct ehci_hcd {
    enum ehci_hrtimer_event next_hrtimer_event;
    unsigned int enabled_hrtimer_events;
    ktime_t[12] hr_timeouts;
    struct hrtimer hrtimer;
    int PSS_poll_count;
    int ASS_poll_count;
    int died_poll_count;
    struct ehci_caps * caps;
    struct ehci_regs * regs;
    struct ehci_dbg_port * debug;
    __u32 hcs_params;
    spinlock_t lock;
    enum ehci_rh_state rh_state;
    bool scanning;
    bool need_rescan;
    bool intr_unlinking;
    bool iaa_in_progress;
    bool async_unlinking;
    bool shutdown;
    struct ehci_qh * qh_scan_next;
    struct ehci_qh * async;
    struct ehci_qh * dummy;
    struct list_head async_unlink;
    struct list_head async_idle;
    unsigned int async_unlink_cycle;
    unsigned int async_count;
    __le32 old_current;
    __le32 old_token;
    unsigned int periodic_size;
    __le32 * periodic;
    dma_addr_t periodic_dma;
    struct list_head intr_qh_list;
    unsigned int i_thresh;
    union ehci_shadow * pshadow;
    struct list_head intr_unlink_wait;
    struct list_head intr_unlink;
    unsigned int intr_unlink_wait_cycle;
    unsigned int intr_unlink_cycle;
    unsigned int now_frame;
    unsigned int last_iso_frame;
    unsigned int intr_count;
    unsigned int isoc_count;
    unsigned int periodic_count;
    unsigned int uframe_periodic_max;
    struct list_head cached_itd_list;
    struct ehci_itd * last_itd_to_free;
    struct list_head cached_sitd_list;
    struct ehci_sitd * last_sitd_to_free;
    long unsigned int[15] reset_done;
    long unsigned int bus_suspended;
    long unsigned int companion_ports;
    long unsigned int owned_ports;
    long unsigned int port_c_suspend;
    long unsigned int suspended_ports;
    long unsigned int resuming_ports;
    struct dma_pool * qh_pool;
    struct dma_pool * qtd_pool;
    struct dma_pool * itd_pool;
    struct dma_pool * sitd_pool;
    unsigned int random_frame;
    long unsigned int next_statechange;
    ktime_t last_periodic_enable;
    u32 command;
    unsigned int no_selective_suspend;
    unsigned int has_fsl_port_bug;
    unsigned int has_fsl_hs_errata;
    unsigned int has_fsl_susp_errata;
    unsigned int big_endian_mmio;
    unsigned int big_endian_desc;
    unsigned int big_endian_capbase;
    unsigned int has_amcc_usb23;
    unsigned int need_io_watchdog;
    unsigned int amd_pll_fix;
    unsigned int use_dummy_qh;
    unsigned int has_synopsys_hc_bug;
    unsigned int frame_index_bug;
    unsigned int need_oc_pp_cycle;
    unsigned int imx28_write_fix;
    __le32 * ohci_hcctrl_reg;
    unsigned int has_hostpc;
    unsigned int has_tdi_phy_lpm;
    unsigned int has_ppcd;
    u8 sbrn;
    struct ehci_stats stats;
    struct dentry * debug_dir;
    u8[64] bandwidth;
    u8[64] tt_budget;
    struct list_head tt_list;
    long unsigned int[0] priv;
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

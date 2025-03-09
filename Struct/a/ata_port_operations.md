# Struct: <code>ata_port_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_device *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_device *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_device *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    enum ata_completion_errors (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    enum ata_completion_errors (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    enum ata_completion_errors (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    enum ata_completion_errors (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    enum ata_completion_errors (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, __le16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    enum ata_completion_errors (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    unsigned int (*)(struct ata_device *, unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, __le16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    enum ata_completion_errors (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    void (*)(struct ata_queued_cmd *) qc_fill_rtf;
    void (*)(struct ata_port *, u64) qc_ncq_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    unsigned int (*)(struct ata_device *, unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, __le16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    enum ata_completion_errors (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    void (*)(struct ata_queued_cmd *) qc_fill_rtf;
    void (*)(struct ata_port *, u64) qc_ncq_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    unsigned int (*)(struct ata_device *, unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, __le16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    const struct ata_port_operations * inherits;
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
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
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
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ata_port_operations {
    int (*)(struct ata_queued_cmd *) qc_defer;
    int (*)(struct ata_queued_cmd *) check_atapi_dma;
    void (*)(struct ata_queued_cmd *) qc_prep;
    unsigned int (*)(struct ata_queued_cmd *) qc_issue;
    bool (*)(struct ata_queued_cmd *) qc_fill_rtf;
    int (*)(struct ata_port *) cable_detect;
    long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter;
    void (*)(struct ata_port *, struct ata_device *) set_piomode;
    void (*)(struct ata_port *, struct ata_device *) set_dmamode;
    int (*)(struct ata_link *, struct ata_device * *) set_mode;
    unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id;
    void (*)(struct ata_device *) dev_config;
    void (*)(struct ata_port *) freeze;
    void (*)(struct ata_port *) thaw;
    ata_prereset_fn_t prereset;
    ata_reset_fn_t softreset;
    ata_reset_fn_t hardreset;
    ata_postreset_fn_t postreset;
    ata_prereset_fn_t pmp_prereset;
    ata_reset_fn_t pmp_softreset;
    ata_reset_fn_t pmp_hardreset;
    ata_postreset_fn_t pmp_postreset;
    void (*)(struct ata_port *) error_handler;
    void (*)(struct ata_port *) lost_interrupt;
    void (*)(struct ata_queued_cmd *) post_internal_cmd;
    void (*)(struct ata_port *) sched_eh;
    void (*)(struct ata_port *) end_eh;
    int (*)(struct ata_link *, unsigned int, u32 *) scr_read;
    int (*)(struct ata_link *, unsigned int, u32) scr_write;
    void (*)(struct ata_port *) pmp_attach;
    void (*)(struct ata_port *) pmp_detach;
    int (*)(struct ata_link *, enum ata_lpm_policy, unsigned int) set_lpm;
    int (*)(struct ata_port *, pm_message_t) port_suspend;
    int (*)(struct ata_port *) port_resume;
    int (*)(struct ata_port *) port_start;
    void (*)(struct ata_port *) port_stop;
    void (*)(struct ata_host *) host_stop;
    void (*)(struct ata_port *, unsigned int) sff_dev_select;
    void (*)(struct ata_port *, u8) sff_set_devctl;
    u8 (*)(struct ata_port *) sff_check_status;
    u8 (*)(struct ata_port *) sff_check_altstatus;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_tf_load;
    void (*)(struct ata_port *, struct ata_taskfile *) sff_tf_read;
    void (*)(struct ata_port *, const struct ata_taskfile *) sff_exec_command;
    unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer;
    void (*)(struct ata_port *) sff_irq_on;
    bool (*)(struct ata_port *) sff_irq_check;
    void (*)(struct ata_port *) sff_irq_clear;
    void (*)(struct ata_queued_cmd *) sff_drain_fifo;
    void (*)(struct ata_queued_cmd *) bmdma_setup;
    void (*)(struct ata_queued_cmd *) bmdma_start;
    void (*)(struct ata_queued_cmd *) bmdma_stop;
    u8 (*)(struct ata_port *) bmdma_status;
    ssize_t (*)(struct ata_port *, char *) em_show;
    ssize_t (*)(struct ata_port *, const char *, size_t) em_store;
    ssize_t (*)(struct ata_device *, char *) sw_activity_show;
    ssize_t (*)(struct ata_device *, enum sw_activity) sw_activity_store;
    ssize_t (*)(struct ata_port *, u32, ssize_t) transmit_led_message;
    void (*)(struct ata_port *) phy_reset;
    void (*)(struct ata_port *) eng_timeout;
    const struct ata_port_operations * inherits;
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
<b>Field type changed. </b>
<code>unsigned int (*)(struct ata_device *, unsigned char *, unsigned int, int) sff_data_xfer</code> ➡️ <code>unsigned int (*)(struct ata_queued_cmd *, unsigned char *, unsigned int, int) sff_data_xfer</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct ata_queued_cmd *) qc_prep</code> ➡️ <code>enum ata_completion_errors (*)(struct ata_queued_cmd *) qc_prep</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int (*)(struct ata_device *, struct ata_taskfile *, u16 *) read_id</code> ➡️ <code>unsigned int (*)(struct ata_device *, struct ata_taskfile *, __le16 *) read_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int (*)(struct ata_device *, long unsigned int) mode_filter</code> ➡️ <code>unsigned int (*)(struct ata_device *, unsigned int) mode_filter</code>
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
<code>void (*)(struct ata_port *, u64) qc_ncq_fill_rtf</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct ata_queued_cmd *) qc_fill_rtf</code> ➡️ <code>void (*)(struct ata_queued_cmd *) qc_fill_rtf</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct ata_port *) phy_reset</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct ata_port *) eng_timeout</code>
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

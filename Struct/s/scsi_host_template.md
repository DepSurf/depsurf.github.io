# Struct: <code>scsi_host_template</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    int (*)(struct scsi_host_template *) detect;
    int (*)(struct Scsi_Host *) release;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, int, void *) ioctl;
    int (*)(struct scsi_device *, int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int no_async_abort;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    struct list_head legacy_hosts;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
    bool disable_blk_mq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    int (*)(struct scsi_host_template *) detect;
    int (*)(struct Scsi_Host *) release;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, int, void *) ioctl;
    int (*)(struct scsi_device *, int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int no_async_abort;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    struct list_head legacy_hosts;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    int (*)(struct scsi_host_template *) detect;
    int (*)(struct Scsi_Host *) release;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, int, void *) ioctl;
    int (*)(struct scsi_device *, int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int no_async_abort;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    struct list_head legacy_hosts;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    int (*)(struct scsi_host_template *) detect;
    int (*)(struct Scsi_Host *) release;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, int, void *) ioctl;
    int (*)(struct scsi_device *, int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    struct list_head legacy_hosts;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    int (*)(struct scsi_host_template *) detect;
    int (*)(struct Scsi_Host *) release;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, int, void *) ioctl;
    int (*)(struct scsi_device *, int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    struct list_head legacy_hosts;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, int, void *) ioctl;
    int (*)(struct scsi_device *, int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, int, void *) ioctl;
    int (*)(struct scsi_device *, int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) init_cmd_priv;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) exit_cmd_priv;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    bool (*)(struct request *) dma_need_drain;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
    int rpm_autosuspend_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) init_cmd_priv;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) exit_cmd_priv;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    bool (*)(struct request *) dma_need_drain;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
    int rpm_autosuspend_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    unsigned int cmd_size;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) init_cmd_priv;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) exit_cmd_priv;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct Scsi_Host *, unsigned int) mq_poll;
    bool (*)(struct request *) dma_need_drain;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    bool (*)(struct scsi_cmnd *) eh_should_retry_cmd;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    struct scsi_host_cmd_pool * cmd_pool;
    int rpm_autosuspend_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    unsigned int cmd_size;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) init_cmd_priv;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) exit_cmd_priv;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct Scsi_Host *, unsigned int) mq_poll;
    bool (*)(struct request *) dma_need_drain;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    bool (*)(struct scsi_cmnd *) eh_should_retry_cmd;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    struct scsi_host_cmd_pool * cmd_pool;
    int rpm_autosuspend_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    unsigned int cmd_size;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) init_cmd_priv;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) exit_cmd_priv;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct Scsi_Host *, unsigned int) mq_poll;
    bool (*)(struct request *) dma_need_drain;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    bool (*)(struct scsi_cmnd *) eh_should_retry_cmd;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int max_host_blocked;
    const struct attribute_group * * shost_groups;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    int rpm_autosuspend_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    unsigned int cmd_size;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) init_cmd_priv;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) exit_cmd_priv;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    void (*)(struct Scsi_Host *) map_queues;
    int (*)(struct Scsi_Host *, unsigned int) mq_poll;
    bool (*)(struct request *) dma_need_drain;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum scsi_timeout_action (*)(struct scsi_cmnd *) eh_timed_out;
    bool (*)(struct scsi_cmnd *) eh_should_retry_cmd;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int max_host_blocked;
    const struct attribute_group * * shost_groups;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    int rpm_autosuspend_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    unsigned int cmd_size;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) init_cmd_priv;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) exit_cmd_priv;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    void (*)(struct Scsi_Host *) map_queues;
    int (*)(struct Scsi_Host *, unsigned int) mq_poll;
    bool (*)(struct request *) dma_need_drain;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum scsi_timeout_action (*)(struct scsi_cmnd *) eh_timed_out;
    bool (*)(struct scsi_cmnd *) eh_should_retry_cmd;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int queuecommand_may_block;
    unsigned int max_host_blocked;
    const struct attribute_group * * shost_groups;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    int rpm_autosuspend_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    unsigned int cmd_size;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) init_cmd_priv;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) exit_cmd_priv;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    void (*)(struct Scsi_Host *) map_queues;
    int (*)(struct Scsi_Host *, unsigned int) mq_poll;
    bool (*)(struct request *) dma_need_drain;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum scsi_timeout_action (*)(struct scsi_cmnd *) eh_timed_out;
    bool (*)(struct scsi_cmnd *) eh_should_retry_cmd;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int queuecommand_may_block;
    unsigned int max_host_blocked;
    const struct attribute_group * * shost_groups;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    int rpm_autosuspend_delay;
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
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
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
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct scsi_host_template {
    struct module * module;
    const char * name;
    const char * (*)(struct Scsi_Host *) info;
    int (*)(struct scsi_device *, unsigned int, void *) ioctl;
    int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl;
    int (*)(struct Scsi_Host *, struct scsi_cmnd *) queuecommand;
    void (*)(struct Scsi_Host *, u16) commit_rqs;
    int (*)(struct scsi_cmnd *) eh_abort_handler;
    int (*)(struct scsi_cmnd *) eh_device_reset_handler;
    int (*)(struct scsi_cmnd *) eh_target_reset_handler;
    int (*)(struct scsi_cmnd *) eh_bus_reset_handler;
    int (*)(struct scsi_cmnd *) eh_host_reset_handler;
    int (*)(struct scsi_device *) slave_alloc;
    int (*)(struct scsi_device *) slave_configure;
    void (*)(struct scsi_device *) slave_destroy;
    int (*)(struct scsi_target *) target_alloc;
    void (*)(struct scsi_target *) target_destroy;
    int (*)(struct Scsi_Host *, long unsigned int) scan_finished;
    void (*)(struct Scsi_Host *) scan_start;
    int (*)(struct scsi_device *, int) change_queue_depth;
    int (*)(struct Scsi_Host *) map_queues;
    int (*)(struct scsi_device *, struct block_device *, sector_t, int *) bios_param;
    void (*)(struct scsi_device *) unlock_native_capacity;
    int (*)(struct seq_file *, struct Scsi_Host *) show_info;
    int (*)(struct Scsi_Host *, char *, int) write_info;
    enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out;
    int (*)(struct Scsi_Host *, int) host_reset;
    const char * proc_name;
    struct proc_dir_entry * proc_dir;
    int can_queue;
    int this_id;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    short int cmd_per_lun;
    unsigned char present;
    int tag_alloc_policy;
    unsigned int track_queue_depth;
    unsigned int supported_mode;
    unsigned int unchecked_isa_dma;
    unsigned int emulated;
    unsigned int skip_settle_delay;
    unsigned int no_write_same;
    unsigned int force_blk_mq;
    unsigned int max_host_blocked;
    struct device_attribute * * shost_attrs;
    struct device_attribute * * sdev_attrs;
    const struct attribute_group * * sdev_groups;
    u64 vendor_id;
    unsigned int cmd_size;
    struct scsi_host_cmd_pool * cmd_pool;
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
<b>Field removed. </b>
<code>bool disable_blk_mq</code>
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
<code>int (*)(struct Scsi_Host *) map_queues</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int no_async_abort</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct scsi_host_cmd_pool * cmd_pool</code> ➡️ <code>struct scsi_host_cmd_pool * cmd_pool</code>
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
<code>unsigned int force_blk_mq</code>
</li>
<li>
<b>Field added. </b>
<code>const struct attribute_group * * sdev_groups</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct scsi_host_template *) detect</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct Scsi_Host *) release</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head legacy_hosts</code>
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
<code>unsigned int max_segment_size</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int use_clustering</code>
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
<code>long unsigned int virt_boundary_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct scsi_device *, int, void *) ioctl</code> ➡️ <code>int (*)(struct scsi_device *, unsigned int, void *) ioctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct scsi_device *, int, void *) compat_ioctl</code> ➡️ <code>int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl</code>
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
<code>void (*)(struct Scsi_Host *, u16) commit_rqs</code>
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
<code>int (*)(struct Scsi_Host *, struct scsi_cmnd *) init_cmd_priv</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct Scsi_Host *, struct scsi_cmnd *) exit_cmd_priv</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct request *) dma_need_drain</code>
</li>
<li>
<b>Field added. </b>
<code>int rpm_autosuspend_delay</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int force_blk_mq</code>
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
<code>unsigned int host_tagset</code>
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
<code>int (*)(struct Scsi_Host *, unsigned int) mq_poll</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct scsi_cmnd *) eh_should_retry_cmd</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int unchecked_isa_dma</code>
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
<code>const struct attribute_group * * shost_groups</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device_attribute * * shost_attrs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device_attribute * * sdev_attrs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct scsi_host_cmd_pool * cmd_pool</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct proc_dir_entry * proc_dir</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char present</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct Scsi_Host *) map_queues</code> ➡️ <code>void (*)(struct Scsi_Host *) map_queues</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum blk_eh_timer_return (*)(struct scsi_cmnd *) eh_timed_out</code> ➡️ <code>enum scsi_timeout_action (*)(struct scsi_cmnd *) eh_timed_out</code>
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
<code>unsigned int queuecommand_may_block</code>
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
<b>Field removed. </b>
<code>int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl</code>
</li>
</ul>
</details>
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
<code>int (*)(struct scsi_device *, unsigned int, void *) compat_ioctl</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

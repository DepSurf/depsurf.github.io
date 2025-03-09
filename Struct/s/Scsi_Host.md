# Struct: <code>Scsi_Host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct scsi_host_cmd_pool * cmd_pool;
    spinlock_t free_list_lock;
    struct list_head free_list;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_queue_tag * bqt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    unsigned int nr_hw_queues;
    long unsigned int cmd_serial_number;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_blk_mq;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int no_scsi2_lun_in_cdb;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    struct request_queue * uspace_req_q;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    struct list_head sht_legacy_list;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct scsi_host_cmd_pool * cmd_pool;
    spinlock_t free_list_lock;
    struct list_head free_list;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_queue_tag * bqt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    unsigned int nr_hw_queues;
    long unsigned int cmd_serial_number;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_blk_mq;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int no_scsi2_lun_in_cdb;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    struct request_queue * uspace_req_q;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    struct list_head sht_legacy_list;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct scsi_host_cmd_pool * cmd_pool;
    spinlock_t free_list_lock;
    struct list_head free_list;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_queue_tag * bqt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    unsigned int nr_hw_queues;
    long unsigned int cmd_serial_number;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_blk_mq;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int no_scsi2_lun_in_cdb;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    struct request_queue * uspace_req_q;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    struct list_head sht_legacy_list;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_queue_tag * bqt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    unsigned int nr_hw_queues;
    long unsigned int cmd_serial_number;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_blk_mq;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int no_scsi2_lun_in_cdb;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    struct request_queue * uspace_req_q;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    struct list_head sht_legacy_list;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_queue_tag * bqt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    unsigned int nr_hw_queues;
    long unsigned int cmd_serial_number;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_blk_mq;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int no_scsi2_lun_in_cdb;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    struct list_head sht_legacy_list;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_queue_tag * bqt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    long unsigned int dma_boundary;
    unsigned int nr_hw_queues;
    long unsigned int cmd_serial_number;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int use_clustering;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_blk_mq;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int no_scsi2_lun_in_cdb;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    unsigned int nr_hw_queues;
    long unsigned int cmd_serial_number;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int no_scsi2_lun_in_cdb;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int nr_maps;
    unsigned int active_mode;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_abort_list;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int nr_maps;
    unsigned int active_mode;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_abort_list;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int nr_maps;
    unsigned int active_mode;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_abort_list;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct kref tagset_refcnt;
    struct completion tagset_freed;
    struct blk_mq_tag_set tag_set;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int opt_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int nr_maps;
    unsigned int active_mode;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_abort_list;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    const struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct kref tagset_refcnt;
    struct completion tagset_freed;
    struct blk_mq_tag_set tag_set;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int opt_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int nr_maps;
    unsigned int active_mode;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int queuecommand_may_block;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_abort_list;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    const struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct kref tagset_refcnt;
    struct completion tagset_freed;
    struct blk_mq_tag_set tag_set;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int opt_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int nr_maps;
    unsigned int active_mode;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int host_tagset;
    unsigned int queuecommand_may_block;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
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
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
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
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct Scsi_Host {
    struct list_head __devices;
    struct list_head __targets;
    struct list_head starved_list;
    spinlock_t default_lock;
    spinlock_t * host_lock;
    struct mutex scan_mutex;
    struct list_head eh_cmd_q;
    struct task_struct * ehandler;
    struct completion * eh_action;
    wait_queue_head_t host_wait;
    struct scsi_host_template * hostt;
    struct scsi_transport_template * transportt;
    struct blk_mq_tag_set tag_set;
    atomic_t host_busy;
    atomic_t host_blocked;
    unsigned int host_failed;
    unsigned int host_eh_scheduled;
    unsigned int host_no;
    int eh_deadline;
    long unsigned int last_reset;
    unsigned int max_channel;
    unsigned int max_id;
    u64 max_lun;
    unsigned int unique_id;
    short unsigned int max_cmd_len;
    int this_id;
    int can_queue;
    short int cmd_per_lun;
    short unsigned int sg_tablesize;
    short unsigned int sg_prot_tablesize;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    long unsigned int dma_boundary;
    long unsigned int virt_boundary_mask;
    unsigned int nr_hw_queues;
    unsigned int active_mode;
    unsigned int unchecked_isa_dma;
    unsigned int host_self_blocked;
    unsigned int reverse_ordering;
    unsigned int tmf_in_progress;
    unsigned int async_scan;
    unsigned int eh_noresume;
    unsigned int no_write_same;
    unsigned int use_cmd_list;
    unsigned int short_inquiry;
    unsigned int no_scsi2_lun_in_cdb;
    char[20] work_q_name;
    struct workqueue_struct * work_q;
    struct workqueue_struct * tmf_work_q;
    unsigned int max_host_blocked;
    unsigned int prot_capabilities;
    unsigned char prot_guard_type;
    long unsigned int base;
    long unsigned int io_port;
    unsigned char n_io_port;
    unsigned char dma_channel;
    unsigned int irq;
    enum scsi_host_state shost_state;
    struct device shost_gendev;
    struct device shost_dev;
    void * shost_data;
    struct device * dma_dev;
    long unsigned int[0] hostdata;
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
<b>Field removed. </b>
<code>struct scsi_host_cmd_pool * cmd_pool</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t free_list_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head free_list</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct request_queue * uspace_req_q</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct list_head sht_legacy_list</code>
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
<code>struct blk_queue_tag * bqt</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int use_clustering</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int use_blk_mq</code>
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
<b>Field removed. </b>
<code>long unsigned int cmd_serial_number</code>
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
<b>Field removed. </b>
<code>atomic_t host_busy</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int use_cmd_list</code>
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
<code>unsigned int nr_maps</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int unchecked_isa_dma</code>
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
<code>struct list_head eh_abort_list</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct kref tagset_refcnt</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion tagset_freed</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int opt_sectors</code>
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
<li>
<b>Field type changed. </b>
<code>struct scsi_host_template * hostt</code> ➡️ <code>const struct scsi_host_template * hostt</code>
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

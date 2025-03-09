# Struct: <code>scsi_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    struct scsi_cmnd * current_cmnd;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    char type;
    char scsi_level;
    char inq_periph_qual;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    int vpd_pg83_len;
    unsigned char * vpd_pg83;
    int vpd_pg80_len;
    unsigned char * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    unsigned int sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    enum scsi_device_state sdev_state;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    int vpd_pg83_len;
    unsigned char * vpd_pg83;
    int vpd_pg80_len;
    unsigned char * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    unsigned int sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int synchronous_alua;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    enum scsi_device_state sdev_state;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    int vpd_pg83_len;
    unsigned char * vpd_pg83;
    int vpd_pg80_len;
    unsigned char * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    unsigned int sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int synchronous_alua;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    enum scsi_device_state sdev_state;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    int vpd_pg83_len;
    unsigned char * vpd_pg83;
    int vpd_pg80_len;
    unsigned char * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    unsigned int sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg0;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    struct scsi_vpd * vpd_pg89;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int set_dbd_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    unsigned int rpm_autosuspend;
    bool offline_already;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    size_t dma_drain_len;
    void * dma_drain_buf;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    atomic_t restarts;
    spinlock_t list_lock;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg0;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    struct scsi_vpd * vpd_pg89;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int set_dbd_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    unsigned int rpm_autosuspend;
    bool offline_already;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    size_t dma_drain_len;
    void * dma_drain_buf;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    struct sbitmap budget_map;
    atomic_t device_blocked;
    atomic_t restarts;
    spinlock_t list_lock;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg0;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    struct scsi_vpd * vpd_pg89;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int set_dbd_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    unsigned int rpm_autosuspend;
    bool offline_already;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    size_t dma_drain_len;
    void * dma_drain_buf;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    struct sbitmap budget_map;
    atomic_t device_blocked;
    atomic_t restarts;
    spinlock_t list_lock;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg0;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    struct scsi_vpd * vpd_pg89;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int set_dbd_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    unsigned int rpm_autosuspend;
    unsigned int ignore_media_change;
    bool offline_already;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    size_t dma_drain_len;
    void * dma_drain_buf;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    struct bsg_device * bsg_dev;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    struct sbitmap budget_map;
    atomic_t device_blocked;
    atomic_t restarts;
    spinlock_t list_lock;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg0;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    struct scsi_vpd * vpd_pg89;
    struct scsi_vpd * vpd_pgb0;
    struct scsi_vpd * vpd_pgb1;
    struct scsi_vpd * vpd_pgb2;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int set_dbd_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    unsigned int rpm_autosuspend;
    unsigned int ignore_media_change;
    unsigned int silence_suspend;
    unsigned int queue_stopped;
    bool offline_already;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    size_t dma_drain_len;
    void * dma_drain_buf;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    struct bsg_device * bsg_dev;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    struct sbitmap budget_map;
    atomic_t device_blocked;
    atomic_t restarts;
    spinlock_t list_lock;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg0;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    struct scsi_vpd * vpd_pg89;
    struct scsi_vpd * vpd_pgb0;
    struct scsi_vpd * vpd_pgb1;
    struct scsi_vpd * vpd_pgb2;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int set_dbd_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int use_16_for_sync;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    unsigned int rpm_autosuspend;
    unsigned int ignore_media_change;
    unsigned int silence_suspend;
    unsigned int queue_stopped;
    bool offline_already;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    atomic_t iotmo_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    size_t dma_drain_len;
    void * dma_drain_buf;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    struct bsg_device * bsg_dev;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    struct sbitmap budget_map;
    atomic_t device_blocked;
    atomic_t restarts;
    spinlock_t list_lock;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg0;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    struct scsi_vpd * vpd_pg89;
    struct scsi_vpd * vpd_pgb0;
    struct scsi_vpd * vpd_pgb1;
    struct scsi_vpd * vpd_pgb2;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int set_dbd_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int use_16_for_sync;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int no_start_on_resume;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    unsigned int rpm_autosuspend;
    unsigned int ignore_media_change;
    unsigned int silence_suspend;
    unsigned int no_vpd_size;
    unsigned int cdl_supported;
    unsigned int cdl_enable;
    unsigned int queue_stopped;
    bool offline_already;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    atomic_t iotmo_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    size_t dma_drain_len;
    void * dma_drain_buf;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    struct bsg_device * bsg_dev;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    struct sbitmap budget_map;
    atomic_t device_blocked;
    atomic_t restarts;
    spinlock_t list_lock;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg0;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    struct scsi_vpd * vpd_pg89;
    struct scsi_vpd * vpd_pgb0;
    struct scsi_vpd * vpd_pgb1;
    struct scsi_vpd * vpd_pgb2;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int manage_system_start_stop;
    unsigned int manage_runtime_start_stop;
    unsigned int manage_shutdown;
    unsigned int force_runtime_start_on_system_start;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int set_dbd_for_ms;
    unsigned int read_before_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int use_16_for_sync;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    unsigned int rpm_autosuspend;
    unsigned int ignore_media_change;
    unsigned int silence_suspend;
    unsigned int no_vpd_size;
    unsigned int cdl_supported;
    unsigned int cdl_enable;
    unsigned int queue_stopped;
    bool offline_already;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    atomic_t iotmo_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    size_t dma_drain_len;
    void * dma_drain_buf;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    struct bsg_device * bsg_dev;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
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
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
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
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct scsi_device {
    struct Scsi_Host * host;
    struct request_queue * request_queue;
    struct list_head siblings;
    struct list_head same_target_siblings;
    atomic_t device_busy;
    atomic_t device_blocked;
    spinlock_t list_lock;
    struct list_head cmd_list;
    struct list_head starved_entry;
    short unsigned int queue_depth;
    short unsigned int max_queue_depth;
    short unsigned int last_queue_full_depth;
    short unsigned int last_queue_full_count;
    long unsigned int last_queue_full_time;
    long unsigned int queue_ramp_up_period;
    long unsigned int last_queue_ramp_up;
    unsigned int id;
    unsigned int channel;
    u64 lun;
    unsigned int manufacturer;
    unsigned int sector_size;
    void * hostdata;
    unsigned char type;
    char scsi_level;
    char inq_periph_qual;
    struct mutex inquiry_mutex;
    unsigned char inquiry_len;
    unsigned char * inquiry;
    const char * vendor;
    const char * model;
    const char * rev;
    struct scsi_vpd * vpd_pg83;
    struct scsi_vpd * vpd_pg80;
    unsigned char current_tag;
    struct scsi_target * sdev_target;
    blist_flags_t sdev_bflags;
    unsigned int eh_timeout;
    unsigned int removable;
    unsigned int changed;
    unsigned int busy;
    unsigned int lockable;
    unsigned int locked;
    unsigned int borken;
    unsigned int disconnect;
    unsigned int soft_reset;
    unsigned int sdtr;
    unsigned int wdtr;
    unsigned int ppr;
    unsigned int tagged_supported;
    unsigned int simple_tags;
    unsigned int was_reset;
    unsigned int expecting_cc_ua;
    unsigned int use_10_for_rw;
    unsigned int use_10_for_ms;
    unsigned int no_report_opcodes;
    unsigned int no_write_same;
    unsigned int use_16_for_rw;
    unsigned int skip_ms_page_8;
    unsigned int skip_ms_page_3f;
    unsigned int skip_vpd_pages;
    unsigned int try_vpd_pages;
    unsigned int use_192_bytes_for_3f;
    unsigned int no_start_on_add;
    unsigned int allow_restart;
    unsigned int manage_start_stop;
    unsigned int start_stop_pwr_cond;
    unsigned int no_uld_attach;
    unsigned int select_no_atn;
    unsigned int fix_capacity;
    unsigned int guess_capacity;
    unsigned int retry_hwerror;
    unsigned int last_sector_bug;
    unsigned int no_read_disc_info;
    unsigned int no_read_capacity_16;
    unsigned int try_rc_10_first;
    unsigned int security_supported;
    unsigned int is_visible;
    unsigned int wce_default_on;
    unsigned int no_dif;
    unsigned int broken_fua;
    unsigned int lun_in_cdb;
    unsigned int unmap_limit_for_ws;
    atomic_t disk_events_disable_depth;
    long unsigned int[1] supported_events;
    long unsigned int[1] pending_events;
    struct list_head event_list;
    struct work_struct event_work;
    unsigned int max_device_blocked;
    atomic_t iorequest_cnt;
    atomic_t iodone_cnt;
    atomic_t ioerr_cnt;
    struct device sdev_gendev;
    struct device sdev_dev;
    struct execute_work ew;
    struct work_struct requeue_work;
    struct scsi_device_handler * handler;
    void * handler_data;
    unsigned char access_state;
    struct mutex state_mutex;
    enum scsi_device_state sdev_state;
    struct task_struct * quiesced_by;
    long unsigned int[0] sdev_data;
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
<code>struct mutex inquiry_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int synchronous_alua</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char access_state</code>
</li>
<li>
<b>Field removed. </b>
<code>struct scsi_cmnd * current_cmnd</code>
</li>
</ul>
</details>
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
<code>unsigned int security_supported</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex state_mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int synchronous_alua</code>
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
<code>unsigned int unmap_limit_for_ws</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * quiesced_by</code>
</li>
<li>
<b>Field removed. </b>
<code>int vpd_pg83_len</code>
</li>
<li>
<b>Field removed. </b>
<code>int vpd_pg80_len</code>
</li>
<li>
<b>Field type changed. </b>
<code>char type</code> ➡️ <code>unsigned char type</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char * vpd_pg83</code> ➡️ <code>struct scsi_vpd * vpd_pg83</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char * vpd_pg80</code> ➡️ <code>struct scsi_vpd * vpd_pg80</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int sdev_bflags</code> ➡️ <code>blist_flags_t sdev_bflags</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>struct scsi_vpd * vpd_pg0</code>
</li>
<li>
<b>Field added. </b>
<code>struct scsi_vpd * vpd_pg89</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int set_dbd_for_ms</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int rpm_autosuspend</code>
</li>
<li>
<b>Field added. </b>
<code>bool offline_already</code>
</li>
<li>
<b>Field added. </b>
<code>size_t dma_drain_len</code>
</li>
<li>
<b>Field added. </b>
<code>void * dma_drain_buf</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head cmd_list</code>
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
<code>atomic_t restarts</code>
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
<code>struct sbitmap budget_map</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t device_busy</code>
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
<code>unsigned int ignore_media_change</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sg_timeout</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sg_reserved_size</code>
</li>
<li>
<b>Field added. </b>
<code>struct bsg_device * bsg_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char current_tag</code>
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
<code>struct scsi_vpd * vpd_pgb0</code>
</li>
<li>
<b>Field added. </b>
<code>struct scsi_vpd * vpd_pgb1</code>
</li>
<li>
<b>Field added. </b>
<code>struct scsi_vpd * vpd_pgb2</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int silence_suspend</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int queue_stopped</code>
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
<code>unsigned int use_16_for_sync</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t iotmo_cnt</code>
</li>
<li>
<b>Field removed. </b>
<code>struct execute_work ew</code>
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
<code>unsigned int no_start_on_resume</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int no_vpd_size</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cdl_supported</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cdl_enable</code>
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
<code>unsigned int manage_system_start_stop</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int manage_runtime_start_stop</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int manage_shutdown</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int force_runtime_start_on_system_start</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int read_before_ms</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int manage_start_stop</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int no_start_on_resume</code>
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

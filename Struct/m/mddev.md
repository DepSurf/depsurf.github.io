# Struct: <code>mddev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    int ready;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time_t ctime;
    time_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    atomic_t writes_pending;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set * bio_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    struct work_struct flush_work;
    struct work_struct event_work;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    atomic_t writes_pending;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set * bio_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    struct work_struct flush_work;
    struct work_struct event_work;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    atomic_t writes_pending;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set * bio_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    struct work_struct flush_work;
    struct work_struct event_work;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set * bio_set;
    struct bio_set * sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    struct work_struct flush_work;
    struct work_struct event_work;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set * bio_set;
    struct bio_set * sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    struct work_struct flush_work;
    struct work_struct event_work;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    mempool_t * flush_pool;
    mempool_t * flush_bio_pool;
    struct work_struct event_work;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    mempool_t * flush_pool;
    mempool_t * flush_bio_pool;
    struct work_struct event_work;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * wb_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * wb_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
    bool fail_last_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    mempool_t md_io_pool;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * serial_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    unsigned int noio_flag;
    bool has_superblocks;
    bool fail_last_dev;
    bool serialize_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct kernfs_node * sysfs_completed;
    struct kernfs_node * sysfs_degraded;
    struct kernfs_node * sysfs_level;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    mempool_t md_io_pool;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t prev_flush_start;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * serial_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    unsigned int noio_flag;
    bool has_superblocks;
    bool fail_last_dev;
    bool serialize_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct kernfs_node * sysfs_completed;
    struct kernfs_node * sysfs_degraded;
    struct kernfs_node * sysfs_level;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t prev_flush_start;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * serial_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    unsigned int noio_flag;
    bool has_superblocks;
    bool fail_last_dev;
    bool serialize_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct kernfs_node * sysfs_completed;
    struct kernfs_node * sysfs_degraded;
    struct kernfs_node * sysfs_level;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    const struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio_set io_acct_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t prev_flush_start;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * serial_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    unsigned int noio_flag;
    bool has_superblocks;
    bool fail_last_dev;
    bool serialize_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct kernfs_node * sysfs_completed;
    struct kernfs_node * sysfs_degraded;
    struct kernfs_node * sysfs_level;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    const struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio_set io_acct_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t prev_flush_start;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * serial_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    unsigned int noio_flag;
    bool has_superblocks;
    bool fail_last_dev;
    bool serialize_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct kernfs_node * sysfs_completed;
    struct kernfs_node * sysfs_degraded;
    struct kernfs_node * sysfs_level;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    const struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio_set io_acct_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t prev_flush_start;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * serial_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    unsigned int noio_flag;
    bool has_superblocks;
    bool fail_last_dev;
    bool serialize_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    struct percpu_ref active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct kernfs_node * sysfs_completed;
    struct kernfs_node * sysfs_degraded;
    struct kernfs_node * sysfs_level;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    const struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio_set io_acct_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t prev_flush_start;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * serial_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    unsigned int noio_flag;
    struct list_head deleting;
    bool has_superblocks;
    bool fail_last_dev;
    bool serialize_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    struct mutex suspend_mutex;
    struct percpu_ref active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct kernfs_node * sysfs_completed;
    struct kernfs_node * sysfs_degraded;
    struct kernfs_node * sysfs_level;
    struct work_struct del_work;
    struct work_struct sync_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    const struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio_set io_clone_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t prev_flush_start;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * serial_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    unsigned int noio_flag;
    struct list_head deleting;
    struct mutex sync_mutex;
    atomic_t sync_seq;
    bool has_superblocks;
    bool fail_last_dev;
    bool serialize_policy;
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
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * wb_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
    bool fail_last_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * wb_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
    bool fail_last_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * wb_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
    bool fail_last_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * wb_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
    bool fail_last_dev;
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
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * wb_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
    bool fail_last_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * wb_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
    bool fail_last_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * wb_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
    bool fail_last_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mddev {
    void * private;
    struct md_personality * pers;
    dev_t unit;
    int md_minor;
    struct list_head disks;
    long unsigned int flags;
    long unsigned int sb_flags;
    int suspended;
    atomic_t active_io;
    int ro;
    int sysfs_active;
    struct gendisk * gendisk;
    struct kobject kobj;
    int hold_active;
    int major_version;
    int minor_version;
    int patch_version;
    int persistent;
    int external;
    char[17] metadata_type;
    int chunk_sectors;
    time64_t ctime;
    time64_t utime;
    int level;
    int layout;
    char[16] clevel;
    int raid_disks;
    int max_disks;
    sector_t dev_sectors;
    sector_t array_sectors;
    int external_size;
    __u64 events;
    int can_decrease_events;
    char[16] uuid;
    sector_t reshape_position;
    int delta_disks;
    int new_level;
    int new_layout;
    int new_chunk_sectors;
    int reshape_backwards;
    struct md_thread * thread;
    struct md_thread * sync_thread;
    char * last_sync_action;
    sector_t curr_resync;
    sector_t curr_resync_completed;
    long unsigned int resync_mark;
    sector_t resync_mark_cnt;
    sector_t curr_mark_cnt;
    sector_t resync_max_sectors;
    atomic64_t resync_mismatches;
    sector_t suspend_lo;
    sector_t suspend_hi;
    int sync_speed_min;
    int sync_speed_max;
    int parallel_resync;
    int ok_start_degraded;
    long unsigned int recovery;
    int recovery_disabled;
    int in_sync;
    struct mutex open_mutex;
    struct mutex reconfig_mutex;
    atomic_t active;
    atomic_t openers;
    int changed;
    int degraded;
    atomic_t recovery_active;
    wait_queue_head_t recovery_wait;
    sector_t recovery_cp;
    sector_t resync_min;
    sector_t resync_max;
    struct kernfs_node * sysfs_state;
    struct kernfs_node * sysfs_action;
    struct work_struct del_work;
    spinlock_t lock;
    wait_queue_head_t sb_wait;
    atomic_t pending_writes;
    unsigned int safemode;
    unsigned int safemode_delay;
    struct timer_list safemode_timer;
    struct percpu_ref writes_pending;
    int sync_checkers;
    struct request_queue * queue;
    struct bitmap * bitmap;
    struct (anon) bitmap_info;
    atomic_t max_corr_read_errors;
    struct list_head all_mddevs;
    struct attribute_group * to_remove;
    struct bio_set bio_set;
    struct bio_set sync_set;
    struct bio * flush_bio;
    atomic_t flush_pending;
    ktime_t start_flush;
    ktime_t last_flush;
    struct work_struct flush_work;
    struct work_struct event_work;
    mempool_t * wb_info_pool;
    void (*)(struct mddev *, struct md_rdev *) sync_super;
    struct md_cluster_info * cluster_info;
    unsigned int good_device_nr;
    bool has_superblocks;
    bool fail_last_dev;
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
<code>unsigned int good_device_nr</code>
</li>
<li>
<b>Field removed. </b>
<code>int ready</code>
</li>
<li>
<b>Field type changed. </b>
<code>time_t ctime</code> ➡️ <code>time64_t ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>time_t utime</code> ➡️ <code>time64_t utime</code>
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
<code>long unsigned int sb_flags</code>
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
<code>int sync_checkers</code>
</li>
<li>
<b>Field added. </b>
<code>struct bio_set * sync_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t writes_pending</code> ➡️ <code>struct percpu_ref writes_pending</code>
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
<code>mempool_t * flush_pool</code>
</li>
<li>
<b>Field added. </b>
<code>mempool_t * flush_bio_pool</code>
</li>
<li>
<b>Field added. </b>
<code>bool has_superblocks</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bio * flush_bio</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t flush_pending</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct flush_work</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bio_set * bio_set</code> ➡️ <code>struct bio_set bio_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bio_set * sync_set</code> ➡️ <code>struct bio_set sync_set</code>
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
<code>struct bio * flush_bio</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t flush_pending</code>
</li>
<li>
<b>Field added. </b>
<code>ktime_t start_flush</code>
</li>
<li>
<b>Field added. </b>
<code>ktime_t last_flush</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct flush_work</code>
</li>
<li>
<b>Field added. </b>
<code>mempool_t * wb_info_pool</code>
</li>
<li>
<b>Field removed. </b>
<code>mempool_t * flush_pool</code>
</li>
<li>
<b>Field removed. </b>
<code>mempool_t * flush_bio_pool</code>
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
<code>bool fail_last_dev</code>
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
<code>mempool_t md_io_pool</code>
</li>
<li>
<b>Field added. </b>
<code>mempool_t * serial_info_pool</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int noio_flag</code>
</li>
<li>
<b>Field added. </b>
<code>bool serialize_policy</code>
</li>
<li>
<b>Field removed. </b>
<code>mempool_t * wb_info_pool</code>
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
<code>struct kernfs_node * sysfs_completed</code>
</li>
<li>
<b>Field added. </b>
<code>struct kernfs_node * sysfs_degraded</code>
</li>
<li>
<b>Field added. </b>
<code>struct kernfs_node * sysfs_level</code>
</li>
<li>
<b>Field added. </b>
<code>ktime_t prev_flush_start</code>
</li>
<li>
<b>Field removed. </b>
<code>ktime_t last_flush</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>mempool_t md_io_pool</code>
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
<code>struct bio_set io_acct_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct attribute_group * to_remove</code> ➡️ <code>const struct attribute_group * to_remove</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
<code>struct list_head deleting</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t active_io</code> ➡️ <code>struct percpu_ref active_io</code>
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
<code>struct mutex suspend_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct sync_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct bio_set io_clone_set</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex sync_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t sync_seq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bio_set io_acct_set</code>
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

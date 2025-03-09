# Struct: <code>mapped_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct srcu_struct io_barrier;
    struct mutex suspend_lock;
    atomic_t holders;
    atomic_t open_count;
    struct dm_table * map;
    struct list_head table_devices;
    struct mutex table_devices_lock;
    long unsigned int flags;
    struct request_queue * queue;
    unsigned int type;
    struct mutex type_lock;
    struct target_type * immutable_target_type;
    struct gendisk * disk;
    char[16] name;
    void * interface_ptr;
    atomic_t[2] pending;
    wait_queue_head_t wait;
    struct work_struct work;
    struct bio_list deferred;
    spinlock_t deferred_lock;
    struct workqueue_struct * wq;
    mempool_t * io_pool;
    mempool_t * rq_pool;
    struct bio_set * bs;
    atomic_t event_nr;
    wait_queue_head_t eventq;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    struct super_block * frozen_sb;
    struct block_device * bdev;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct bio flush_bio;
    unsigned int internal_suspend_count;
    struct dm_stats stats;
    struct kthread_worker kworker;
    struct task_struct * kworker_task;
    unsigned int seq_rq_merge_deadline_usecs;
    int last_rq_rw;
    sector_t last_rq_pos;
    ktime_t last_rq_start_time;
    struct blk_mq_tag_set tag_set;
    bool use_blk_mq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct srcu_struct io_barrier;
    struct mutex suspend_lock;
    void * map;
    struct list_head table_devices;
    struct mutex table_devices_lock;
    long unsigned int flags;
    struct request_queue * queue;
    int numa_node_id;
    unsigned int type;
    struct mutex type_lock;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    struct gendisk * disk;
    char[16] name;
    void * interface_ptr;
    atomic_t[2] pending;
    wait_queue_head_t wait;
    struct work_struct work;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct workqueue_struct * wq;
    mempool_t * io_pool;
    mempool_t * rq_pool;
    struct bio_set * bs;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct block_device * bdev;
    struct dm_kobject_holder kobj_holder;
    struct bio flush_bio;
    struct dm_stats stats;
    struct kthread_worker kworker;
    struct task_struct * kworker_task;
    unsigned int seq_rq_merge_deadline_usecs;
    int last_rq_rw;
    sector_t last_rq_pos;
    ktime_t last_rq_start_time;
    struct blk_mq_tag_set * tag_set;
    bool use_blk_mq;
    bool init_tio_pdu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct srcu_struct io_barrier;
    struct mutex suspend_lock;
    void * map;
    struct list_head table_devices;
    struct mutex table_devices_lock;
    long unsigned int flags;
    struct request_queue * queue;
    int numa_node_id;
    unsigned int type;
    struct mutex type_lock;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    struct gendisk * disk;
    char[16] name;
    void * interface_ptr;
    atomic_t[2] pending;
    wait_queue_head_t wait;
    struct work_struct work;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct workqueue_struct * wq;
    mempool_t * io_pool;
    mempool_t * rq_pool;
    struct bio_set * bs;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct block_device * bdev;
    struct dm_kobject_holder kobj_holder;
    struct bio flush_bio;
    struct dm_stats stats;
    struct kthread_worker kworker;
    struct task_struct * kworker_task;
    unsigned int seq_rq_merge_deadline_usecs;
    int last_rq_rw;
    sector_t last_rq_pos;
    ktime_t last_rq_start_time;
    struct blk_mq_tag_set * tag_set;
    bool use_blk_mq;
    bool init_tio_pdu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct srcu_struct io_barrier;
    struct mutex suspend_lock;
    void * map;
    struct list_head table_devices;
    struct mutex table_devices_lock;
    long unsigned int flags;
    struct request_queue * queue;
    int numa_node_id;
    enum dm_queue_mode type;
    struct mutex type_lock;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    char[16] name;
    void * interface_ptr;
    atomic_t[2] pending;
    wait_queue_head_t wait;
    struct work_struct work;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct workqueue_struct * wq;
    mempool_t * io_pool;
    struct bio_set * bs;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct block_device * bdev;
    struct dm_kobject_holder kobj_holder;
    struct bio flush_bio;
    struct dm_stats stats;
    struct kthread_worker kworker;
    struct task_struct * kworker_task;
    unsigned int seq_rq_merge_deadline_usecs;
    int last_rq_rw;
    sector_t last_rq_pos;
    ktime_t last_rq_start_time;
    struct blk_mq_tag_set * tag_set;
    bool use_blk_mq;
    bool init_tio_pdu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    void * map;
    struct list_head table_devices;
    struct mutex table_devices_lock;
    long unsigned int flags;
    struct request_queue * queue;
    int numa_node_id;
    enum dm_queue_mode type;
    struct mutex type_lock;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    char[16] name;
    void * interface_ptr;
    atomic_t[2] pending;
    wait_queue_head_t wait;
    struct work_struct work;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct workqueue_struct * wq;
    mempool_t * io_pool;
    struct bio_set * bs;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct block_device * bdev;
    struct dm_kobject_holder kobj_holder;
    struct bio flush_bio;
    struct dm_stats stats;
    struct kthread_worker kworker;
    struct task_struct * kworker_task;
    unsigned int seq_rq_merge_deadline_usecs;
    int last_rq_rw;
    sector_t last_rq_pos;
    ktime_t last_rq_start_time;
    struct blk_mq_tag_set * tag_set;
    bool use_blk_mq;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    atomic_t[2] pending;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct bio flush_bio;
    struct dm_stats stats;
    struct kthread_worker kworker;
    struct task_struct * kworker_task;
    unsigned int seq_rq_merge_deadline_usecs;
    int last_rq_rw;
    sector_t last_rq_pos;
    ktime_t last_rq_start_time;
    struct blk_mq_tag_set * tag_set;
    bool use_blk_mq;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    int swap_bios;
    struct semaphore swap_bios_semaphore;
    struct mutex swap_bios_lock;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    int swap_bios;
    struct semaphore swap_bios_semaphore;
    struct mutex swap_bios_lock;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    int swap_bios;
    struct semaphore swap_bios_semaphore;
    struct mutex swap_bios_lock;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
    unsigned int nr_zones;
    unsigned int * zwp_offset;
    struct dm_ima_measurements ima;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    wait_queue_head_t wait;
    long unsigned int * pending_io;
    struct hd_geometry geometry;
    struct workqueue_struct * wq;
    struct work_struct work;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    bool init_tio_pdu;
    struct blk_mq_tag_set * tag_set;
    struct dm_stats stats;
    unsigned int internal_suspend_count;
    int swap_bios;
    struct semaphore swap_bios_semaphore;
    struct mutex swap_bios_lock;
    struct dm_md_mempools * mempools;
    struct dm_kobject_holder kobj_holder;
    struct srcu_struct io_barrier;
    unsigned int nr_zones;
    unsigned int * zwp_offset;
    struct dm_ima_measurements ima;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    wait_queue_head_t wait;
    long unsigned int * pending_io;
    struct hd_geometry geometry;
    struct workqueue_struct * wq;
    struct work_struct work;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    struct work_struct requeue_work;
    struct dm_io * requeue_list;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    bool init_tio_pdu;
    struct blk_mq_tag_set * tag_set;
    struct dm_stats stats;
    unsigned int internal_suspend_count;
    int swap_bios;
    struct semaphore swap_bios_semaphore;
    struct mutex swap_bios_lock;
    struct dm_md_mempools * mempools;
    struct dm_kobject_holder kobj_holder;
    struct srcu_struct io_barrier;
    unsigned int nr_zones;
    unsigned int * zwp_offset;
    struct dm_ima_measurements ima;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    wait_queue_head_t wait;
    long unsigned int * pending_io;
    struct hd_geometry geometry;
    struct workqueue_struct * wq;
    struct work_struct work;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    struct work_struct requeue_work;
    struct dm_io * requeue_list;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    bool init_tio_pdu;
    struct blk_mq_tag_set * tag_set;
    struct dm_stats stats;
    unsigned int internal_suspend_count;
    int swap_bios;
    struct semaphore swap_bios_semaphore;
    struct mutex swap_bios_lock;
    struct dm_md_mempools * mempools;
    struct dm_kobject_holder kobj_holder;
    struct srcu_struct io_barrier;
    unsigned int nr_zones;
    unsigned int * zwp_offset;
    struct dm_ima_measurements ima;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    wait_queue_head_t wait;
    long unsigned int * pending_io;
    struct hd_geometry geometry;
    struct workqueue_struct * wq;
    struct work_struct work;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    struct work_struct requeue_work;
    struct dm_io * requeue_list;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    bool init_tio_pdu;
    struct blk_mq_tag_set * tag_set;
    struct dm_stats stats;
    unsigned int internal_suspend_count;
    int swap_bios;
    struct semaphore swap_bios_semaphore;
    struct mutex swap_bios_lock;
    struct dm_md_mempools * mempools;
    struct dm_kobject_holder kobj_holder;
    struct srcu_struct io_barrier;
    unsigned int nr_zones;
    unsigned int * zwp_offset;
    struct dm_ima_measurements ima;
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
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
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
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mapped_device {
    struct mutex suspend_lock;
    struct mutex table_devices_lock;
    struct list_head table_devices;
    void * map;
    long unsigned int flags;
    struct mutex type_lock;
    enum dm_queue_mode type;
    int numa_node_id;
    struct request_queue * queue;
    atomic_t holders;
    atomic_t open_count;
    struct dm_target * immutable_target;
    struct target_type * immutable_target_type;
    char[16] name;
    struct gendisk * disk;
    struct dax_device * dax_dev;
    struct work_struct work;
    wait_queue_head_t wait;
    spinlock_t deferred_lock;
    struct bio_list deferred;
    void * interface_ptr;
    wait_queue_head_t eventq;
    atomic_t event_nr;
    atomic_t uevent_seq;
    struct list_head uevent_list;
    spinlock_t uevent_lock;
    unsigned int internal_suspend_count;
    struct bio_set io_bs;
    struct bio_set bs;
    struct workqueue_struct * wq;
    struct super_block * frozen_sb;
    struct hd_geometry geometry;
    struct dm_kobject_holder kobj_holder;
    struct block_device * bdev;
    struct dm_stats stats;
    struct blk_mq_tag_set * tag_set;
    bool init_tio_pdu;
    struct srcu_struct io_barrier;
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
<code>int numa_node_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct dm_target * immutable_target</code>
</li>
<li>
<b>Field added. </b>
<code>bool init_tio_pdu</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dm_table * map</code> ➡️ <code>void * map</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct blk_mq_tag_set tag_set</code> ➡️ <code>struct blk_mq_tag_set * tag_set</code>
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
<code>struct dax_device * dax_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>mempool_t * rq_pool</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int type</code> ➡️ <code>enum dm_queue_mode type</code>
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
<code>struct bio_set io_bs</code>
</li>
<li>
<b>Field removed. </b>
<code>mempool_t * io_pool</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bio_set * bs</code> ➡️ <code>struct bio_set bs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t[2] pending</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bio flush_bio</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kthread_worker kworker</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_struct * kworker_task</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int seq_rq_merge_deadline_usecs</code>
</li>
<li>
<b>Field removed. </b>
<code>int last_rq_rw</code>
</li>
<li>
<b>Field removed. </b>
<code>sector_t last_rq_pos</code>
</li>
<li>
<b>Field removed. </b>
<code>ktime_t last_rq_start_time</code>
</li>
<li>
<b>Field removed. </b>
<code>bool use_blk_mq</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int swap_bios</code>
</li>
<li>
<b>Field added. </b>
<code>struct semaphore swap_bios_semaphore</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex swap_bios_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct super_block * frozen_sb</code>
</li>
<li>
<b>Field removed. </b>
<code>struct block_device * bdev</code>
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
<code>unsigned int nr_zones</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int * zwp_offset</code>
</li>
<li>
<b>Field added. </b>
<code>struct dm_ima_measurements ima</code>
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
<code>long unsigned int * pending_io</code>
</li>
<li>
<b>Field added. </b>
<code>struct dm_md_mempools * mempools</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bio_set io_bs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bio_set bs</code>
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
<code>struct work_struct requeue_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct dm_io * requeue_list</code>
</li>
</ul>
</details>
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

# Struct: <code>gendisk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    unsigned int events;
    unsigned int async_events;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct device * driverfs_dev;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    unsigned int events;
    unsigned int async_events;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    unsigned int events;
    unsigned int async_events;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    unsigned int events;
    unsigned int async_events;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    unsigned int events;
    unsigned int async_events;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    unsigned int events;
    unsigned int async_events;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    unsigned int events;
    unsigned int async_events;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    struct cdrom_device_info * cdi;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct block_device * part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    long unsigned int state;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    struct cdrom_device_info * cdi;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    short unsigned int events;
    short unsigned int event_flags;
    struct xarray part_tbl;
    struct block_device * part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    long unsigned int state;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    struct cdrom_device_info * cdi;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    short unsigned int events;
    short unsigned int event_flags;
    struct xarray part_tbl;
    struct block_device * part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    long unsigned int state;
    struct mutex open_mutex;
    unsigned int open_partitions;
    struct backing_dev_info * bdi;
    struct kobject * slave_dir;
    struct list_head slave_bdevs;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    struct cdrom_device_info * cdi;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
    u64 diskseq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    short unsigned int events;
    short unsigned int event_flags;
    struct xarray part_tbl;
    struct block_device * part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    long unsigned int state;
    struct mutex open_mutex;
    unsigned int open_partitions;
    struct backing_dev_info * bdi;
    struct kobject * slave_dir;
    struct list_head slave_bdevs;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    struct cdrom_device_info * cdi;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
    u64 diskseq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    short unsigned int events;
    short unsigned int event_flags;
    struct xarray part_tbl;
    struct block_device * part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    struct bio_set bio_split;
    int flags;
    long unsigned int state;
    struct mutex open_mutex;
    unsigned int open_partitions;
    struct backing_dev_info * bdi;
    struct kobject queue_kobj;
    struct kobject * slave_dir;
    struct list_head slave_bdevs;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    unsigned int nr_zones;
    unsigned int max_open_zones;
    unsigned int max_active_zones;
    long unsigned int * conv_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    struct cdrom_device_info * cdi;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
    u64 diskseq;
    struct blk_independent_access_ranges * ia_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    short unsigned int events;
    short unsigned int event_flags;
    struct xarray part_tbl;
    struct block_device * part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    struct bio_set bio_split;
    int flags;
    long unsigned int state;
    struct mutex open_mutex;
    unsigned int open_partitions;
    struct backing_dev_info * bdi;
    struct kobject queue_kobj;
    struct kobject * slave_dir;
    struct list_head slave_bdevs;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    unsigned int nr_zones;
    unsigned int max_open_zones;
    unsigned int max_active_zones;
    long unsigned int * conv_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    struct cdrom_device_info * cdi;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
    u64 diskseq;
    blk_mode_t open_mode;
    struct blk_independent_access_ranges * ia_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    short unsigned int events;
    short unsigned int event_flags;
    struct xarray part_tbl;
    struct block_device * part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    struct bio_set bio_split;
    int flags;
    long unsigned int state;
    struct mutex open_mutex;
    unsigned int open_partitions;
    struct backing_dev_info * bdi;
    struct kobject queue_kobj;
    struct kobject * slave_dir;
    struct list_head slave_bdevs;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    unsigned int nr_zones;
    unsigned int max_open_zones;
    unsigned int max_active_zones;
    long unsigned int * conv_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    struct cdrom_device_info * cdi;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
    u64 diskseq;
    blk_mode_t open_mode;
    struct blk_independent_access_ranges * ia_ranges;
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
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
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
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct gendisk {
    int major;
    int first_minor;
    int minors;
    char[32] disk_name;
    char * (*)(struct gendisk *, umode_t *) devnode;
    short unsigned int events;
    short unsigned int event_flags;
    struct disk_part_tbl * part_tbl;
    struct hd_struct part0;
    const struct block_device_operations * fops;
    struct request_queue * queue;
    void * private_data;
    int flags;
    struct rw_semaphore lookup_sem;
    struct kobject * slave_dir;
    struct timer_rand_state * random;
    atomic_t sync_io;
    struct disk_events * ev;
    struct kobject integrity_kobj;
    int node_id;
    struct badblocks * bb;
    struct lockdep_map lockdep_map;
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
<code>struct badblocks * bb</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device * driverfs_dev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct lockdep_map lockdep_map</code>
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
<code>struct rw_semaphore lookup_sem</code>
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
<code>short unsigned int event_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int async_events</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int events</code> ➡️ <code>short unsigned int events</code>
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
<code>struct cdrom_device_info * cdi</code>
</li>
<li>
<b>Field removed. </b>
<code>char * (*)(struct gendisk *, umode_t *) devnode</code>
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
<code>long unsigned int state</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rw_semaphore lookup_sem</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct hd_struct part0</code> ➡️ <code>struct block_device * part0</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct disk_part_tbl * part_tbl</code> ➡️ <code>struct xarray part_tbl</code>
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
<code>struct mutex open_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int open_partitions</code>
</li>
<li>
<b>Field added. </b>
<code>struct backing_dev_info * bdi</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head slave_bdevs</code>
</li>
<li>
<b>Field added. </b>
<code>u64 diskseq</code>
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
<code>struct bio_set bio_split</code>
</li>
<li>
<b>Field added. </b>
<code>struct kobject queue_kobj</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int nr_zones</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int max_open_zones</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int max_active_zones</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * conv_zones_bitmap</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * seq_zones_wlock</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_independent_access_ranges * ia_ranges</code>
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
<code>blk_mode_t open_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kobject integrity_kobj</code>
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

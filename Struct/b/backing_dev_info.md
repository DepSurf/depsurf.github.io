# Struct: <code>backing_dev_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    struct list_head bdi_list;
    long unsigned int ra_pages;
    unsigned int capabilities;
    congested_fn * congested_fn;
    void * congested_data;
    char * name;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct radix_tree_root cgwb_tree;
    struct rb_root cgwb_congested_tree;
    atomic_t usage_cnt;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
    struct dentry * debug_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    struct list_head bdi_list;
    long unsigned int ra_pages;
    unsigned int capabilities;
    congested_fn * congested_fn;
    void * congested_data;
    char * name;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct radix_tree_root cgwb_tree;
    struct rb_root cgwb_congested_tree;
    atomic_t usage_cnt;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
    struct dentry * debug_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    char * name;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct radix_tree_root cgwb_tree;
    struct rb_root cgwb_congested_tree;
    atomic_t usage_cnt;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
    struct dentry * debug_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct radix_tree_root cgwb_tree;
    struct rb_root cgwb_congested_tree;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
    struct dentry * debug_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct radix_tree_root cgwb_tree;
    struct rb_root cgwb_congested_tree;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
    struct dentry * debug_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct radix_tree_root cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
    struct dentry * debug_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
    struct dentry * debug_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    char[64] dev_name;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    char[64] dev_name;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    char[64] dev_name;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    char[64] dev_name;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    char[64] dev_name;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    char[64] dev_name;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    char[64] dev_name;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    long unsigned int last_bdp_sleep;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    char[64] dev_name;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
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
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
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
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct backing_dev_info {
    u64 id;
    struct rb_node rb_node;
    struct list_head bdi_list;
    long unsigned int ra_pages;
    long unsigned int io_pages;
    congested_fn * congested_fn;
    void * congested_data;
    const char * name;
    struct kref refcnt;
    unsigned int capabilities;
    unsigned int min_ratio;
    unsigned int max_ratio;
    unsigned int max_prop_frac;
    atomic_long_t tot_write_bandwidth;
    struct bdi_writeback wb;
    struct list_head wb_list;
    struct xarray cgwb_tree;
    struct rb_root cgwb_congested_tree;
    struct mutex cgwb_release_mutex;
    struct rw_semaphore wb_switch_rwsem;
    wait_queue_head_t wb_waitq;
    struct device * dev;
    struct device * owner;
    struct timer_list laptop_mode_wb_timer;
    struct dentry * debug_dir;
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
<code>struct device * owner</code>
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
<code>long unsigned int io_pages</code>
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
<code>struct kref refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t usage_cnt</code>
</li>
<li>
<b>Field type changed. </b>
<code>char * name</code> ➡️ <code>const char * name</code>
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
<code>struct mutex cgwb_release_mutex</code>
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
<code>struct rw_semaphore wb_switch_rwsem</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct radix_tree_root cgwb_tree</code> ➡️ <code>struct xarray cgwb_tree</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct dentry * debug_stats</code>
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
<code>u64 id</code>
</li>
<li>
<b>Field added. </b>
<code>struct rb_node rb_node</code>
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
<code>char[64] dev_name</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>congested_fn * congested_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>void * congested_data</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rb_root cgwb_congested_tree</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
<code>long unsigned int last_bdp_sleep</code>
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
